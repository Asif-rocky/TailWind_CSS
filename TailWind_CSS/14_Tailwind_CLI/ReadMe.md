## HOW TO GENERATE PACKAGE JSON FILE

1. Run the command npm init
2. It will prompt few questions, just press enter for all the things
3. Your package.json file is created now

## How to set up Tailwind CSS via Tailwind CLI

1. Follow the instructions provided in this Tailwind Setup URL
   https://tailwindcss.com/docs/installation/tailwind-cli

## Two ways of starting the Tailwind CLI build process

1. Follow the above Tailwind Setup URL

OR

2. If you wanna manually create build script:
   - first create package.json file as mentioned above
   - second paste the code given below in your package.json file

```
    "scripts": {
        "build": "tailwindcss -i ./input.css -o styles/style.css",
        "watch": "tailwindcss -i ./input.css -o styles/style.css --watch"
     }
```
