# Level Editor Project

Web-based editor designed for creating game levels with predefined assets.

![Level Editor Project preview image](./project-preview.png)

## Hello to [BigDevSoon](https://bigdevsoon.me/) 👋

Create code that matters! 🤩

Level up your coding skills by building real-world projects with professional designs.

## Project brief

Dive deep into the realm of game design and development with **Level Editor**. This web-based editor provides an intuitive platform for crafting engaging game levels with assets. Seamlessly integrate various game assets, utilize responsive zooming features, and ensure that your creations are preserved across sessions. Whether you're a seasoned developer or just stepping into the world of game design, Level Editor promises an immersive and enlightening experience.

### What you will learn

- **Intuitive UI Design**: Create a multi-faceted user interface that not only looks good but functions seamlessly. From asset bars to dynamic zoom indicators, you'll grasp the intricacies of sophisticated web design elements.

- **Advanced Grid Manipulation**: Delve into the world of grids, learning how to dynamically alter their sizes, integrate assets, and provide a responsive user experience at varying zoom levels.

- **Data Handling & Storage**: Learn the importance of persistently storing user creations, ensuring that their efforts aren't lost between sessions. Dive into exporting layouts to JSON and appreciate the power of data representation.

- **Interactive Asset Management**: Get hands-on experience with interactive elements such as hover descriptions, dynamic mouse cursors, and asset selection mechanisms.

### Requirements

- Implement a UI container based on the provided design that includes key elements: an assets vertical bar, a top bar, a content area with a background, an empty grid (15x15 initially), and a bottom bar.
- Enable the selection of assets from the left bar. When an asset is selected, it should be highlighted with a blue outline on the left bar. Change the mouse cursor to the chosen asset, allowing users to draw on the grid either by clicking or dragging. While placing assets, showcase an opacity effect to signify the potential asset position. Initially, no asset is selected, and no action occurs upon a mouse click until an asset is chosen.
- Integrate a "quick asset" feature on the top bar with a hover tooltip. Initially, the first asset serves as the "quick asset" since no drawing has been done. As users draw with an asset, update the "quick asset" to the recent one. Clicking on "quick asset" selects it and highlights it only on the left bar.
- Implement an undo mechanism that allows users to revert actions with a hover tooltip. It should be robust enough to revert back to the initial state (empty grid) without causing application issues. Extend support for keyboard shortcuts (ctrl/cmd + Z) for user convenience.
- Offer an eraser functionality that lets users click or drag to remove assets with a hover tooltip and a selected state. The cursor should dynamically switch to the eraser tool when activated. An opacity effect should also be displayed to indicate potential asset removal.
- Incorporate a zoom feature with a hover tooltip and selected states that start at 100%, capable of zooming in up to 150% and zooming out to 50%. The bottom bar indicators should dynamically display the current zoom level.
- Embed the settings icon with a hover tooltip and a selected state. Add a popup with the export-to-JSON feature on click, providing users the option to rename the file before downloading. The resulting file should represent the grid as a 2D array with 0-x values according to asset indexes.
- Facilitate the adjustment of a grid layout with a base size constraint. As users modify the grid's dimensions, the changes should immediately reflect both within the grid and on the bottom bar indicators.
- Implement a local storage mechanism to retain the user's level configuration, ensuring that their work persists after a page reload. If the user accesses the platform for the first time, present them with either an empty grid or a predefined level, based on creativity.

## Project assets

Each project comes with additional assets to aid your implementation:

**Starter Files**: Get started with project templates, assets, and resources to kickstart your development process. Simple HTML/CSS/JS files are included.

**Project images**: Access a collection of a few chosen preview project images that can be used to enhance your project.

**Unique Screenshots**: Most cards in the project come with unique screenshots that provide visual guidance for your project's design and requirements.

Additionally, you have the option to download the comprehensive Figma Design for 3 BigTokens. This design includes all visual states and a robust Design System to ensure consistency and precision in your implementation. The "Download Figma design" button is available whenever you choose to elevate your project experience.

## Get started

1. Click the "Start Project" button on the project's page in our app to begin your project.
2. Explore the available project assets, including images, starter files, and unique card screenshots to understand the project's scope.
3. For a comprehensive project experience, download the Figma design for 3 BigTokens.
4. Configure your "Coding setup" using Glitch or GitHub if desired.
5. Dive into the project details through the cards for a deeper understanding.
6. Start coding using your preferred technologies.
7. Refer to the documentation or ask for assistance if needed.
8. Submit your solution, let it shine, and share it with other folks!

## Implementation

Embrace the freedom of choice in your implementation. Whether you're using familiar tools or experimenting with new ones, make this project uniquely yours. Use any combination of languages, libraries, or frameworks as you desire. Push boundaries, learn, and make something to be proud of. 😊

**Setup & Environment**: You can use both [Glitch](https://glitch.com/), a cloud-based editor perfect for quick starts and live previews, or [GitHub](https://github.com/) to lay the groundwork. [GitHub](https://github.com/) is an excellent choice for those building a portfolio or keen on mastering Git. If you're new to coding, consider beginning with [Glitch](https://glitch.com/) to bypass the initial Git learning curve.

No matter your platform choice, feel free to overwrite repository files to suit your project structure. We've included a set of starter files and an `assets` folder, extracted from the design, to streamline your setup process.

**Structuring your project**: Whether you're pacing yourself with Freerun's card-by-card approach or diving into the deep end with Speedrun, it's essential to segment your work. Break down the project into smaller components or sections and plan the implementation based on the provided designs.

### Getting help when stuck

**Community**: Reach out to our "Community questions" section in the project for support. Remember, connecting your Discord account grants you 1 BigToken on your first connection!

**ChatGPT**: For intricate, technical concerns, the "ChatGPT" section in the project is at your disposal. A BIG subscription is required to access this feature.

## Review

Before finalizing your project, take a moment to review your work. This process ensures the quality of your code and fosters self-growth:

1. **Self-Review**: Start by examining your own code. Use this time for introspection, checking that you've adhered to the project's goals and requirements.

2. **Community review**: If you're looking for external opinions, our community is a great place to turn. Fellow developers can offer fresh perspectives, pointing out areas for refinement.

3. **ChatGPT review**: Alternatively, if you're after technical insights, the "ChatGPT" section in the project offers in-depth analysis. This AI-powered tool pinpoints areas of improvement and helps to elevate your code quality.

## Guidelines

1. **Project Planning**: Start by reviewing the design and requirements. Get a good grasp of the project's scope. This foresight can save you time and rework later on.

2. **Design Fidelity**: Strive for a close match with the design. However, creative variations are welcome, especially if they enhance UX/UI. Tools like [PixelParallel](https://chrome.google.com/webstore/detail/pixelparallel-by-htmlburg/iffnoibnepbcloaaagchjonfplimpkob?hl=en) can assist in ensuring design accuracy.

3. **Code Quality**: Ensure your code is clean and efficient. Extensions like [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint), for [VSCode](https://code.visualstudio.com/) users, are invaluable. For beginners, platforms like [Glitch](https://glitch.com/) simplify the coding journey.

4. **Tech Stack Choices**: Choose the right technologies that align with the project's needs. Whether it's a particular framework, library, or platform, your choice can impact the project's flexibility, scalability, and efficiency.

5. **Version Control**: While optional, version control systems like Git can be beneficial, especially for larger projects. If you're keen, delve into [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow), but simplicity is fine for newcomers or straightforward projects.

6. **Testing & Quality Assurance**: Prioritize testing to ensure your project runs seamlessly. Conduct both automated tests, using tools like [Jest](https://jestjs.io/), and manual tests to navigate the application as a user would. Vigilance in identifying and rectifying bugs will lead to a more robust and trustworthy final product.

Ultimately, the beauty of this project lies in the journey and the learning. Use tools that make your workflow efficient and add your unique touch to the design. 💡

## Submit solution

Whether you've just begun or are wrapping up, you have the flexibility to submit your project at any stage via the "Submit solution" button. This not only allows for iterative improvements but also offers a chance to garner feedback early on, making your learning more effective.

Here's a quick guide to ensure a smooth submission:

1. **Cloud-Based Editors**: If you're using cloud-based platforms like [Glitch](https://glitch.com/) or [Replit](https://replit.com/), submission is straightforward. These platforms automatically provide you with both code and preview links.

2. **Manual Deployment**: For those who've built projects on local environments or prefer platforms that require manual deployment, consider services like [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/).

3. **Tag Check**: Ensure the `<bds />` tag is present in your `index.html`. This is a crucial step as we'll verify its presence during submission.

4. **Optional Feedback via Discord**: If you've connected your Discord account within our app, you can optionally request feedback during submission. This will initiate a thread on Discord where community members can provide insights. Each thread includes key links such as your repository and preview URL, making it easier for peers to review and comment.

Remember, the aim is not just to finish but to learn and grow. Iterative submissions and community feedback can greatly amplify your learning experience. Best of luck with your project journey!

## Share solution

Celebrating and sharing your accomplishments is a great way to both reinforce your learning and inspire others. Here's how you can do it:

1. **Your Solution**: Once you've submitted your solution, it becomes a part of your portfolio. Share your unique solution link directly from your solution page or use our "Share solution" widget. There, you'll find various social platform buttons to help spread the word effortlessly.

2. **Project Page**: Loved the project? Share the [Level Editor](https://app.bigdevsoon.me/projects/level-editor) with your network. It’s a great way to challenge others and see what they can build.

3. **Invite Friends**: Excited about our platform? Spread the joy! Every time you invite a friend using your unique link found in the Profile or Settings section of our app, and they register, you earn 1 BigToken. Sharing truly is rewarding!

4. **Technical write-up**: Documenting your journey and the technical decisions you made can be an enriching experience. Platforms like [dev.to](https://dev.to/), [HackerNoon](https://hackernoon.com/), and [Medium](http://medium.com/) are excellent places to pen down your thoughts. Not only does it help build your online presence, but it also solidifies your understanding.

5. **Create Free Content**: Making tutorials or content around how you tackled the project can be both fun and educational. Linking back to the project can also drive curiosity and potentially help others in their coding journey.

Remember, every project has a story. Sharing yours might inspire someone else to begin their own. Keep coding, and keep sharing! 🌟

Happy coding! 🚀
