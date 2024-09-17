---
title: "Activity 11: Research Angular Directives"
datePublished: Tue Sep 17 2024 06:15:55 GMT+0000 (Coordinated Universal Time)
cuid: cm161iznm00170ak2cov5d1qd
slug: activity-11-research-angular-directives

---

#### **Instructions:**

### **Definition of Angular Directives**:

* **What are Angular Directives?**  
    Angular **directives** are instructions that Angular uses to manipulate the DOM. Directives allow developers to extend HTML's behavior by applying functionality to HTML elements.
    
* **Types of Angular Directives**:
    

1. **Component Directives**:
    
    * **Definition**: These are the most common directives in Angular. A component directive is simply a custom HTML element that represents a component.
        
    * **Example**: When you declare a component in Angular, it acts as a directive that provides structure and behavior for part of the UI.
        
    * ```typescript
        @Component({
          selector: 'app-root',
          template: `<h1>Hello World</h1>`,
        })
        export class AppComponent {}
        ```
        
    
    **Structural Directives**:
    
    * **Definition**: These directives change the structure of the DOM by adding or removing elements.
        
    * **Common Structural Directives**: `*ngIf`, `*ngFor`, and `*ngSwitch`.
        
    * **Example (**`*ngIf`): Shows or hides elements based on a condition.
        
    * ```typescript
        <div *ngIf="isLoggedIn">Welcome back!</div>
        ```
        
    
2. **Attribute Directives**:
    
    * **Definition**: These directives modify the behavior or appearance of an element.
        
    * **Common Attribute Directives**: `ngClass`, `ngStyle`, and `ngModel`.
        
    * **Example (**`ngClass`): Dynamically adds or removes classes.
        
3. * ```typescript
        <div [ngClass]="{ 'active': isActive }">Toggle me</div>
        ```
        
        ### **Use Cases of Angular Directives**:
        
        * **Component Directives**:
            
            * Used to build UI components that encapsulate logic, structure, and style.
                
            * Example: Creating reusable UI elements like buttons, cards.
                
        * **Structural Directives**:
            
            * `*ngIf`: Conditionally renders content based on a boolean value.
                
            * `*ngFor`: Loops through arrays to generate dynamic lists or tables.
                
            * **Use Case**: For dynamic rendering of elements like showing a list of products or hiding UI elements based on user state.
                
            * ```typescript
                <ul>
                  <li *ngFor="let item of items">{{ item.name }}</li>
                </ul>
                ```
                
        
        **Attribute Directives**:
        
        * **ngClass**: Dynamically changes class names.
            
        * **ngStyle**: Dynamically updates styles based on expressions.
            
        * **Use Case**: Modify the appearance of elements based on conditions (e.g., change button color based on form validation state).
            
        * ```typescript
            <button [ngStyle]="{ 'background-color': isValid ? 'green' : 'red' }">Submit</button>
            ```
            
        
        ### **Code Snippets**:
        
        * **Structural Directive Example** (`*ngIf`):
            
        * ```typescript
            <p *ngIf="user.isAdmin">You have admin privileges</p>
            ```
            
        
        **Attribute Directive Example** (`ngClass`):
        
    * ```typescript
        <div [ngClass]="{ 'highlight': isHighlighted, 'dim': !isHighlighted }">
          This text is conditionally styled
        </div>
        ```
        
        **Structural Directive Example** (`*ngFor`):
        
    * ```typescript
        <ul>
          <li *ngFor="let user of users">{{ user.name }}</li>
        </ul>
        ```
        
    
    **Custom Directive Example**: Create a custom directive to highlight text on hover
    

```typescript
import { Directive, ElementRef, HostListener } from '@angular/core';

@Directive({
  selector: '[appHighlight]'
})
export class HighlightDirective {
  constructor(private el: ElementRef) {}

  @HostListener('mouseenter') onMouseEnter() {
    this.highlight('yellow');
  }

  @HostListener('mouseleave') onMouseLeave() {
    this.highlight(null);
  }

  private highlight(color: string) {
    this.el.nativeElement.style.backgroundColor = color;
  }
}
```