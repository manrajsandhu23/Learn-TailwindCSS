# Learn Tailwind CSS

Writing CSS is a bit tough, that's why this utility exists. In this repo i have added all the code and steps that i followed along learning.

## Learning Sources 📝

[Tailwind Official Documentation](https://tailwindcss.com/docs/installation "Docs Link")

[Tailwind CSS in One Shot By Hitesh Choudhary](https://www.youtube.com/watch?v=_9mTJ84uL1Q "Video Link")

## Installation

```
npx tailwindcss init
```

Add this in CSS Input File

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Configuration

```
// create 2 folders dist and src
// update config file [content]
```

```
For adding CSS Classes
npx tailwind -i [./src/inputFileName] -o [./dist/outputFileName] --watch
```

```
npx tailwind -i ./input.css -o ./style.css --watch
```
