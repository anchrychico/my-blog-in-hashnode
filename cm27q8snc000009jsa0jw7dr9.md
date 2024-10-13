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
```

UseCase-The UserProfileComponent only handles displaying user profiles, while UserService manages data interactions. This separation makes maintenance easier as changes in the user service will not affect the profile component.

2\. Open/Closed Principle (OCP)

Definition: Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification.

Angular Application: Use services and decorators to extend functionality without modifying existing code.

Example: