---
title: "Activity 12 Research Angular Pipes"
datePublished: Tue Sep 17 2024 07:19:07 GMT+0000 (Coordinated Universal Time)
cuid: cm163s9y1000b0akzh022dfmp
slug: activity-12-research-angular-pipes

---

#### **Instructions:**

1. ### **Definition of Angular Pipes**:
    
    * **What are Angular Pipes?**  
        Angular **pipes** are a feature that allows data transformation in templates. They take input data and transform it to a desired output, usually for presentation purposes (e.g., formatting dates, numbers, or strings).
        
        * **Purpose**: To enhance how data is displayed without modifying the underlying logic.
            
        * **Syntax**: Pipes are used in templates with the `|` symbol.
            
        * **Example**:
            
            ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726554866777/99401bf0-bdf7-4742-af10-019770dc0a43.png align="center")
            
    
    ### **Types of Angular Pipes**:
    
    **1.Angular provides many built-in pipes**, including but not limited to:
    
    * **DatePipe**: Formats date objects according to a pattern
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726554914457/73e6eb80-dbee-4999-8a3d-f46ea2ba8e66.png align="center")
        
    
    **CurrencyPipe**: Formats a number as currency
    
2. ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726554973087/70f45d2d-e887-4349-a965-26f2d46b17e4.png align="center")
    
    **DecimalPipe**: Formats a number with decimal points
    
3. ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726555035181/a7d2cc8f-3999-4b4f-aa47-0e677440238f.png align="center")
    
    **UpperCasePipe**: Converts text to uppercase
    
4. ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726555253263/5dfef21d-1a94-4a8f-9ef7-78e5053f1cb3.png align="center")
    
5. **LowerCasePipe**: Converts text to lowercase
    
6. ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726555209890/7a3c4eea-fbe0-4748-8e61-9980aee19ea2.png align="center")
    
    **SlicePipe**: Extracts a portion of a string or array
    
7. ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726555299767/cb2fddc9-ce40-431f-a373-41ae55a5a6d8.png align="center")
    
    **PercentPipe**: Transforms numbers into percentage format
    
8. ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726555431852/f9bf6768-6e6d-41ca-91c9-6f023392a364.png align="center")
    

**2.Use Cases of Angular Pipes**

**Displaying formatted dates**

**Use Case**: Pipes like `DatePipe` are extremely useful for displaying dates in a user-friendly format. This is particularly important when showing dates in a way that is readable and meaningful based on user preferences or locale.

* **Purpose**: To format dates according to a specified pattern, making them more comprehensible (e.g., full date, short date).
    
* **Example**:
    
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726556735718/a4da8e5c-8e59-41da-ad62-5b1dfbf9bc7b.png align="center")
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726556751579/3a55a539-612a-4dbc-aeb4-fa78b799c3da.png align="center")
        
    
    **DatePipe Patterns**:
    
    * `'short'`: e.g., `9/3/2024`
        
    * `'medium'`: e.g., `Mar 9, 2024, 12:00:00 PM`
        
    * `'long'`: e.g., `March 9, 2024 at 12:00:00 PM GMT+01:00`
        
    * `'fullDate'`: e.g., `Saturday, March 9, 2024`
        

### **Converting Text to Uppercase**

**Use Case**: The `UpperCasePipe` is used to standardize text input by converting it to uppercase. This is useful for ensuring consistency in text display, such as showing names or titles in uppercase.

* **Purpose**: To convert all characters in a string to uppercase, making text display uniform.
    
* **Example**:
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726556841403/cc61470a-f6f4-456b-a0f7-64c2e2197301.png align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726557038611/5c5349aa-ff92-4966-889c-0727bc0fbcd2.png align="center")
    
    ### **Handling Financial Data**
    
    **Use Case**: Pipes like `CurrencyPipe` and `DecimalPipe` are essential for formatting financial figures to ensure they are displayed correctly with appropriate currency symbols and decimal places.
    
    * **Purpose**: To format numbers as currency or with specific decimal precision, making financial data clear and consistent.
        
    * **Example (CurrencyPipe)**:
        
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726557511254/307dc5a1-5c31-4034-88b0-e33a1668406b.png align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726557010378/6fa7cc81-dca2-467c-a2e0-eccfdc117731.png align="center")
    
    **Search for Code Snippets**:
    
* **Custom Pipe** that transforms text into title case:
    
* ```typescript
    import { Pipe, PipeTransform } from '@angular/core';
    
    @Pipe({
      name: 'titleCase'
    })
    export class TitleCasePipe implements PipeTransform {
      transform(value: string): string {
        return value.split(' ').map(word => word[0].toUpperCase() + word.slice(1).toLowerCase()).join(' ');
      }
    }
    ```
    

**Usage in Template**:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726557352373/cf84a974-325c-4860-be5d-50571a7715b5.png align="center")

1. **Add References**:
    
    * Cite all the resources and websites where you found information and examples (official Angular documentation, blogs, tutorials).
        
    * Make sure to include links to further reading for users interested in learning more about Angular pipes.
        
    * [https://youtu.be/29jD2BcBX5w?si=kBnje5F2udcqrHcz](https://youtu.be/29jD2BcBX5w?si=kBnje5F2udcqrHcz)