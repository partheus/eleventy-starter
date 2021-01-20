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

## How it works - The site itself

- EleventyJS works as a static site generator. In simple terms, this means that all loading is done superfast, and html files are generated immediately on compilation. There is a set layout for these files, which then become webpages in the browser. 
- The webpages are all based on a certain template. For this site, I've used `liquid` as the templating language. In the `_includes` folder, there is a simple layoud.liquid file. All html files generated from this template will have the same exact layout.
- You can create custom templates! For example, my personal website (https://parth.ninja) has several templates, including a custom footer and header. 

Since this a blog site, you will need to add blog posts from time to time. These will typically be saved under the 

![](/img/screenshot.png)
