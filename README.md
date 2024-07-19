# tailwind-crash-course
Basic setup and usage of tailwind css

## Setup steps
1. Create package JSON <br>
> npm init -y
2. Install TailwindCSS <br>
> npm i tailwindcss
3. Add to src/css <br>
> @tailwind base; <br>
> @tailwind components; <br>
> @tailwind utilities <br>
4. Create stylesheet .css file in public folder <br>
> e.g. dist/style.css
5. Edit script in package.json <br>
> e.g. "build:css": ""build:css": "tailwindcss build -i ./src/input.css -o ./dist/output.css""
6. Run <br>
> npm run build:css
