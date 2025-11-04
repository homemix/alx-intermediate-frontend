# SASS/SCSS Fundamentals Project

## Overview
This project is a **practical introduction to SASS/SCSS**, a powerful CSS preprocessor.  
The goal is to move beyond basic CSS by learning to use features that make stylesheets more **maintainable**, **readable**, and **efficient**.

Through a series of incremental tasks, you’ll explore everything from **setup and compilation** to **variables**, **nesting**, and **mixins**, gaining hands-on experience with modern stylesheet workflows.

---

## Learning Objectives
By the end of this project, you will be able to:

-  Install and configure the **SASS compiler** in a development environment.
- Understand the **core philosophy** of a CSS preprocessor and its advantages over vanilla CSS.
-  Write and compile `.scss` files into standard **CSS**.
-  Apply core SASS features to improve styling efficiency:
    - Use **variables** to store and reuse values (like colors, fonts, sizes).
    - Structure CSS rules using **nesting** to mirror HTML hierarchy.
    - Create reusable code blocks with **mixins** for consistent styles.

---

##  Key Concepts

### SASS/SCSS (Syntactically Awesome Style Sheets)
SASS is a **preprocessor scripting language** that compiles into CSS.  
It introduces features that make styling more modular and developer-friendly.  
`SCSS` is the newer syntax that fully supports traditional CSS syntax while adding SASS power.

---

###  Variables (`$variable-name`)
Variables allow you to **store reusable values** such as colors, fonts, or dimensions.  
This promotes **consistency** and makes **global theme changes** easy.

**Example:**
```scss
$primary-color: #3498db;
body {
  background-color: $primary-color;
}
