
Install tailwind:
```
npm install tailwindcss
or
npm i tailwindcss
```

Tailwind official docs get started:
```
npm i -D tailwindcss
```

The -D flag stands for --save-dev and is used to install a package as a development dependency. Development dependencies are packages that are required to build or develop an application, but are not needed at runtime. For example, testing libraries and build tools are often installed as development dependencies.

In the case of npm install -D tailwindcss, the tailwindcss package would be installed as a development dependency for the current project. This means that it would be listed in the devDependencies section of the project's package.json file, and it would not be included in the production bundle when the application is built for deployment.

To generate the tailwind.config.js file. Run the npx command:
```
npx tailwindcss init
```

Update the content in tailwind.config.js:
```
content: ["./src/**/*.{html,js}"]
```
Start tailwind CLI build process:
```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```