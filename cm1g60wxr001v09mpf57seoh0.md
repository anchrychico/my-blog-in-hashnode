---
title: "ACTIVITY 7: Angular Basic Routing"
datePublished: Tue Sep 24 2024 08:19:31 GMT+0000 (Coordinated Universal Time)
cuid: cm1g60wxr001v09mpf57seoh0
slug: activity-7-angular-basic-routing

---

Goal:

Create a simple Angular project with basic routing and four components: **login**, **signup**, **homepage**, and **landing page**. The project will showcase the use of Angular routing to navigate between these components.

**Step 1**

1. **Create Four Components:**
    
    * Generate the following components using Angular CLI:
        
        * login
            
        * signup
            
        * homepage
            
        * landing page
            
    * Implement basic functionality and structure for each component using **HTML** and **TypeScript** only (no design or CSS required).
        
    * open a IDE, Find the folder you created in the command and go to the terminal type of generate component Homepage.
        

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727163683768/f0c720d1-3fdd-4a50-b489-950a1a8f9580.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727164155052/274283e5-1bdb-4ec1-b8c7-377afad1c788.jpeg align="center")

step 2

**Set Up Routing:**

* Set up Angular routing to navigate between the **login**, **signup**, **homepage**, and **landing page** [components.](http://components.click)
    
* [click](http://components.click) a app.module.ts and type const routes: Routes, @[@NgModule](@NgModule)[, bootstr](https://hashnode.com/@NgModule)ap, declarations, imports, and export class AppModule.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727165039090/7fcc21c5-8992-43af-a8e9-b60969e55f1c.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727164354650/01a4bf51-e527-4fff-8601-46e4683e6695.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727165185254/1cdec1b3-6e25-4766-a607-53521edfc27e.jpeg align="center")

step 3 type a routerlink of component to browser.

go to app component html create and type the

&lt;a routerLink'“/” &gt;Homepage&lt;/a&gt;

&lt;br&gt;

&lt;a routerLink'“Login” &gt;Login&lt;/a&gt;

&lt;br&gt;

&lt;a routerLink'“signup” &gt;Signup&lt;/a&gt;

&lt;br&gt;

&lt;a routerLink'“contact us” &gt;contact us&lt;/a&gt;

&lt;router-outlet&gt;&lt;/router-outlet&gt;

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727165464012/48c5f249-3124-4eb0-99b4-1b408eba3467.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727165863497/464430f0-b6c0-4c14-991b-4dcb7839c540.jpeg align="center")

And after all,this is the output

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727165927073/276062d9-f0fe-40ed-a873-48ef8d42aeaf.jpeg align="center")