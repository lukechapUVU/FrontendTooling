## Vite
1. What problem is this tool trying to solve?
- *Vite aims to make the build process for developers faster and easier.*
2. How does it solve the problem?
- *Vite is designed to work with modern libraries and frameworks. Vite's modular approach also makes it easier for developers to split their code into smaller, more manageable pieces.*
3. When shouldn't you use this tool?
- *Vite might shine in medium scale projects, but it doesn't really hold up in large-sized projects where a more powerful build tool like Webpack is more appropriate.*
4. Name two features you find interesting/useful and explain why they are helpful.
- *Vite has a feature called Hot Module Replacement which allows the developer to see the changes to their code without having to refresh the browser.*
- *Vite supports various JavaScript libraries and frameworks like React, Vue, and Angular.*
5. What other information should someone know before using this tool?
- *In order to setup Vite correctly, you need to have Node.js and npm installed.*

## Parcel
1. What problem is this tool trying to solve?
- *Parcel is designed to solve the problem of complex build tool configurations for web developers. Before Parcel was available, developers had to manually configure and maintain complex build tools.*
2. How does it solve the problem?
- *It automatically analyzes your project's dependencies and creates an optimized bundle for your web application.*
3. When shouldn't you use this tool?
- *Since Parcel configures for you, there are some cases when a custom configuration isn't possible if it isn't supported by Parcel.*
4. Name two features you find interesting/useful and explain why they are helpful.
- *Parcel offers a simple plugin system which makes it easy to extend its functionality and customize it to your needs.*
- *Parcel doesn't require any configuration to start working with it, so you can use the time you would have configuring it to start on your project right away.*
5. What other information should someone know before using this tool?
- *Parcel supports ES6 modules, so it's important to have your code written in this format.*

## Webpack
1. What problem is this tool trying to solve?
- *Webpack can reduce the number of HTTP request required to load a page through its module bundling feature.*
2. How does it solve the problem?
- *Webpack's module bundling works by taking all the parts that make up a web application like CSS files, images, and fonts to name a few and bundling them together into a single, optimized package.*
3. When shouldn't you use this tool?
- *Smaller project managers will find that Webpack is a more powerful tool than they are looking for.*
4. Name two features you find interesting/useful and explain why they are helpful.
- *In addition to the module bundling mentioned earlier, Webpack also has loaders which preprocess and transform files before they're included in your application bundle.*
- *Webpack has a large ecosystem of plugins that extends its functionality.*
5. What other information should someone know before using this tool?
- *Since Webpack is highly configurable, it can take some time to set it up and configure it properly.*

## Compare and Contrast
1. What makes each tool unique?
- *Vite offers a modern architecture and high-speed development server. Parcel requires minimal configuration and supports a wide range of file types. Webpack offers advanced features and plenty of customization options.*
2. What makes them different?
- *Vite focuses on speed and developer experience, Parcel is also focused on developer experience, but it shines in its zero-config feature, and Webpack is more powerful and flexible than the other two.*
3. When would you use one over the other?
- *You would use Vite or Parcel for small to medium sized projects, but Vite offers faster build times whereas Parcel requires less configuration. You would use Webpack if you wanted a more customizable configuration or you have a larger project.*