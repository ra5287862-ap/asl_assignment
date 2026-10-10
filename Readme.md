### Assignment Resources

GitHub Repository: https://github.com/tamimkhan887/ASL_Assignment_Resources

## Requirements

1. **Create the website exactly as shown in the provided reference/design.**
2. Use **only HTML and Tailwind CSS** to build the project.
3. Make a minimum of **5 meaningful Git commits** throughout the development process.
4. **Do not use AI** to complete the assignment.
5. **Deploy the project** on a hosting platform. Netlify is recommended, but GitHub Pages or Vercel may also be used.
6. The website must be **fully responsive** and work properly on mobile, tablet, and desktop devices.

## Important Notice

Students who successfully complete the assignment **without using AI** will receive a **certificate from ASL** for completing the Web Development Journey.

Each assignment will be checked individually. If it is found that AI has been used to complete the project, the student **will not be eligible for the certificate**.

## Support Class

To help students with their difficulties and confusion, a **daily support class** will be conducted at **11:00 PM**.

Students are encouraged to bring their questions, problems, and project-related issues to the support class.

## Submission

Students must complete and bring their projects **by next Friday** for review.

 
## Tailwind CSS Setup — Short Notes

1. `cd D:\ASL_Assignment_Resources-main`
   (Project folder-এ ঢুকেছি)

2. `npm init -y`
   (Node.js project initialize করেছি এবং `package.json` তৈরি করেছি)

3. `npm install tailwindcss @tailwindcss/cli`
   (Tailwind CSS install করেছি)

4. `index.html`
   (Main HTML file তৈরি করেছি)

5. `src` folder
   (CSS files রাখার জন্য folder তৈরি করেছি)

6. `src/input.css`
   (Tailwind CSS-এর input file তৈরি করেছি)

7. `@import "tailwindcss";`
   (Tailwind CSS import করেছি)

8. `npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch`
   (Tailwind CSS build এবং watch mode চালু করেছি)

9. `<link rel="stylesheet" href="./src/output.css">`
   (Generated Tailwind CSS HTML-এর সাথে connect করেছি)

10. `class="text-4xl font-bold text-blue-600"`
    (Tailwind CSS কাজ করছে কিনা test করেছি)

11. `npm run dev`
    (Tailwind CSS development mode-এ চালানোর জন্য script তৈরি করেছি)

## Final Project Structure

```text
ASL_Assignment_Resources-main/
│
├── src/
│   ├── input.css
│   └── output.css
│
├── index.html
├── package.json
├── package-lock.json
└── node_modules/
```

**Tailwind CSS Setup Complete ✅**
