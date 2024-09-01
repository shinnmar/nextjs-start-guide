# Next.js start guide 🐣

## 1. How to add more than one class using CSS Modules in Next.js

if you're using Sass with CSS Modules you can use more than one class, you'll need to use Template Literal (``) to make it work.
In this example "content" is the first class, "row" will be the second and "flex-center" our third class:

### structure
``` ruby
    {`${styles.firstClass} secondClass thirdClass etc`}
```
### example in file.tsx
``` ruby
    <div className={`${styles.content} row flex-center`}>
      <h2>This is a test</h2>
    </div>
```

### HTML:
![image](https://github.com/user-attachments/assets/e22da068-b4a8-4296-bf2e-47f5b71441c5)
