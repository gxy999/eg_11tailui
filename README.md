# eg_11tailui
This is a starter kit for [11ty](https://www.11ty.dev/), with [tailwindcss](https://tailwindcss.com/), and [daisyui](https://daisyui.com/). 

## To use
1. Download or clone the repository
2. In the terminal: `npm install` to download the dependencies
3. Then: `npm run dev` to build and start the dev server 
4. Visit [http://localhost:8080](http://localhost:8080) to view the site
5. To stop the server (in order to change configurations or recompile tailwind, for example) just press `control + C`, then `npm run dev` again to rebuild.

## Notes
This is a fairly standard implementation with only a few customizations. Below are the most notable files and their basic functions.
+ Files are read from `/src` and built to `/dist`
+ Templating is done with nunjucks `.njk` by default
+ Content pages are in markdown `.md` (with native HTML processing)
+ The `src/assets` directory is passed through to `dist`
+ Google fonts have been added and commented out
+ Nav and footer components with theme toggle