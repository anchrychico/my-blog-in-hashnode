---
title: "Activity 25:SOLID PRINCIPLES IN ANGULAR"
datePublished: Sun Oct 13 2024 15:15:18 GMT+0000 (Coordinated Universal Time)
cuid: cm27q8snc000009jsa0jw7dr9
slug: activity-25solid-principles-in-angular

---

1\. Single Responsibility Principle (SRP)

Definition: A class should have one, and only one, reason to change. This means that a class should have only one job or responsibility.

Angular Application: In Angular, each component, service, or directive should focus on a single responsibility.

Example:

```xml
@Component({
  selector: 'app-user-profile',
  templateUrl: './user-profile.component.html',
})
export class UserProfileComponent {
  constructor(private userService: UserService) {}
  
  getUserInfo(userId: string) {
    // Fetch user information
  }
}
```

UseCase-The UserProfileComponent only handles displaying user profiles, while UserService manages data interactions. This separation makes maintenance easier as changes in the user service will not affect the profile component.

2\. Open/Closed Principle (OCP)

Definition: Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification.

Angular Application: Use services and decorators to extend functionality without modifying existing code.

Example:

```xml
abstract class Notification {
  abstract send(message: string): void;
}

class EmailNotification extends Notification {
  send(message: string) {
    // Send email
  }
}

class SMSNotification extends Notification {
  send(message: string) {
    // Send SMS
  }
}
```

Use Case: If you need to add a new notification method, such as PushNotification, you can create a new class without changing the existing classes.

3\. Liskov Substitution Principle (LSP)

Definition: If S is a subtype of T, then objects of type T may be replaced with objects of type S without affecting the correctness of the program.

Angular Application: Ensure that components or services that extend other classes can be used interchangeably.

Example:

```xml
class Car {

  start() { return 'Engine starts'; }

}

class Tesla extends Car {

  start() { return 'Tesla engine starts silently'; }

}
```

Use Case: You can pass any type of Car (including Tesla) to startCar, ensuring that your application remains flexible and functional.

4\. Interface Segregation Principle (ISP)

Definition: No client should be forced to depend on methods it does not use.

Angular Application: Create smaller, specific interfaces instead of a large, general-purpose interface.

Example:

```xml
print();

}

interface Scanner {

  scan();

}

class MultiFunctionDevice implements Printer, Scanner {

  print() {

    // Implementation

  }

  scan() {

    // Implementation
```

Use Case: Instead of creating a large Device interface with all methods, we split it into Printer and Scanner, allowing clients to implement only the interfaces they need.

5\. Dependency Inversion Principle (DIP)

Definition: High-level modules should not depend on low-level modules. Both should depend on abstractions.

Angular Application: Use dependency injection in services and components.

Example:

```xml
@Injectable({
```

Use Case: The UserService does not depend directly on a concrete implementation of API calls. Instead, it relies on the ApiService, which can be mocked or replaced seamlessly during testing.

And it's my link Github

[https://github.com/anchrychico/Activity-25-SOLID-PRINCIPLES-in-Angular/blob/main/README.md?plain=1](https://github.com/anchrychico/Activity-25-SOLID-PRINCIPLES-in-Angular/blob/main/README.md?plain=1)