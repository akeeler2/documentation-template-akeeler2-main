# Documentation Template

_This project does not include a draft stage. You do not need to create a "draft" branch in VS Code and can start working right away in the "main" branch._

## Description

Create an organized and responsive content area that includes four images, each paired with a caption, and one paragraph of text. This will serve as a template for the documentation section required in future projects, which will include sketches, wireframes, and a description.

## Procedures

### Prep

1. Gather 4 high-quality photos from [Unsplash](https://unsplash.com), another stock photo site, or your own original image files. Pay attention to the aspect ratios in your wireframe and selected photos. You may want to crop all of the images to the same aspect ratio (if possible) to simplify layout decisions.
2. Use [Squoosh](https://squoosh.app) or your preferred photo editing application to resize and compress images according to the IMS322 Docs [Style Guide](https://ersheff.github.io/IMS322-Docs/style-guide/#image-compression-resolution-and-organization) and [Optimizing Images](https://ersheff.github.io/IMS322-Docs/ref/optimizing-images/) pages.
3. Copy the prepared image files to the `images` folder in your project folder in VS Code.

### Content

1. Create one or more flexible layout containers to act as rows or columns, replicating your wireframe.
2. Populate the flexible containers with elements for your image containers, images, captions, and paragraph.
3. Insert `src` and `alt` attributes for all `<img>` elements to display your chosen photos. Remember that you will need to include the folder name as part of the path to the file, e.g., `images/dog.webp`.
4. Fill the caption and paragraph elements with placeholder text. Each caption should be a few words in length, while the paragraph should be a few sentences.
   1. You can create placeholder text in VS Code by typing `loremX` and pressing the tab key, replacing `X` with the desired number of words (e.g., `lorem20` will autofill 20 words).

### Styling

1. Ensure that your images are fluid. This is best accomplished by keeping the `width: 100%` property that is provided in the `style.css` file of the assignment template and using image container elements like `<div>` or `<figure>`.
2. Depending on your layout, apply `display: flex` or `display: grid` to the main flexible layout containers. Adjust additional flexbox and grid properties as needed.
3. Choose an appropriate font that satisfies the [Style Guide](https://ersheff.github.io/IMS322-Docs/style-guide/#font-selection-and-loading) requirements and apply it to all text elements (this should be the same font used in your wireframe).
4. Carefully consider how you will accommodate the [display size targets](https://ersheff.github.io/IMS322-Docs/style-guide/#display-size-targets-and-general-layout) from the Style Guide. You may need to adjust the provided media queries to adapt to all sizes. Regardless of window size, your images should remain large enough to show sufficient detail without exceeding the window width or distorting the aspect ratio.

### Interactivity and Dynamic Behavior

_There should not be any JavaScript in this assignment. Please keep a blank `script.js` file in your project folder to satisfy the [Default Files](https://ersheff.github.io/IMS322-Docs/style-guide/#default-files) requirement from the Style Guide._

## Submission

_This project does not include a draft stage. You will only need to stage, commit, and sync changes in the "main" branch. It is recommended that you Stage and Commit after each major change (steps 1-3) and Sync often (step 4), even before you are finished._

1. Open the **Source Control** panel in VS Code.
2. Stage all changes by clicking the **+** next to **Changes**.
3. Enter a commit message and click the **Commit** button (use "finished" for your final commit).
4. The **Commit** button should change to a **Sync Changes** button. Click this to finish syncing the latest changes to your online GitHub repository.
5. Find your repository on GitHub.
6. Go to the **Settings** tab within the repository and navigate to the **Pages** section.
7. Under **Branch**, choose the appropriate branch (draft or main) and click **Save**.
8. After a few moments, if you refresh the page, there should now be a URL near the top next to a **Visit Site** button. If you click this button, you should see your site open in a new window.
9. Copy the URL generated by GitHub Pages, paste it in the Website URL field of the corresponding Canvas assignment, and click **Submit Assignment**.

## Grading

**27 points total**

Refer to the rubric on Canvas for detailed grading criteria.

Points will _not_ be awarded for any portions of the submission that do not comply with the Artificial Intelligence and Grading Policies outlined in the syllabus:

- If using GitHub Copilot, export the session as a .json file by opening the **Command Palette** in VS Code and running "Chat: Export Session…" Save this file in your project folder before submission.
- Any code submitted using statements or structures not covered by class documentation, examples, or demonstrations must include a link to the source as comments in the code. You are expected to use class techniques when generating code using GitHub Copilot.