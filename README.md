# eleventy-starter
A simple template for myself to get familiar with the folder structure for eleventy. The site is extremely barebones, with just a couple lines of CSS/styling, without pagination or tags. If you're looking for a fool-proof solution for a text-heavy blog site, you're in the right place. View the live demo [here](https://eleventy-barebones-starter.netlify.app/).

## GitHub
In case the GitHub ecosystem is unfamiliar to you, please check out the official [starter guide](https://guides.github.com/activities/hello-world/)! 

# Getting started:
Run the following commands in your local terminal:

    cd my-workspace
    
    git clone --depth=1 https://github.com/partheus/eleventy-starter.git my-eleventy-blog
    
    cd my-eleventy-blog
    
    npm install

The project is now ready to go live! Run the following command to bring up a local environment with hot reload (any changes you make in the local text editor will reflect immediately in the browser window):

    npm run dev
    
Open http://localhost:8080 in a browser of your choice. If everything was done right, you should see the homepage of the starter blog! Screenshot attached below. You're now ready to start customizing the site according to your needs! For further help, check out the official 11ty docs here: https://www.11ty.dev/docs/

![](/img/homepage-ss.png)

## How it works - The site itself

- EleventyJS works as a static site generator. In simple terms, this means that all loading is done superfast, and html files are generated immediately on compilation. There is a set layout for these files, which then become webpages in the browser. 
- The webpages are all based on a certain template. For this site, I've used `liquid` as the templating language. In the `_includes` folder, there is a simple `layout.liquid` file. All html files generated from this template will have the same exact layout.
- You can create custom templates! For example, my personal website (https://parth.ninja) has several templates, including a custom footer and header.
- When you run the commands to compile all files, a set of ready-to-be-published files are generated in the `_site` folder.
- Other resources are stored in the `/css` and `/img` folders. The `/writing/posts` folder is explained in the next section.

## Blog posts

- Since this a blog site, you will need to add blog posts from time to time. These will be saved in the `/writing/posts` folder.
- The easiest way I've found of doing this is as follows:

Install the `npx` package manager using the following command:

    npm install -g npx

Add a blog post with the default layout (an example is shown below) with the file extension as `.md` inside `/writing/posts`.
![](/img/blog-layout-ss.png)

Run the following command to compile the files:
    
    npx eleventy

Then, run the following command to bring up the live reload site locally:
    
    npx eleventy --serve

This command serves the same purpose as `npm run dev` as we saw earlier. You should be able to visit http://localhost:8080 and see your site all set up!

## The colors and fonts

- The master `css` file is located under `/css`. Any changes you make to this file will be reflected in your site immediately.

Happy blogging!





