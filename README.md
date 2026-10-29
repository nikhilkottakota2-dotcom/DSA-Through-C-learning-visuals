# Algorithm Visual Lab

A responsive, interactive website for learning sorting, searching, stacks, and queues through step-by-step visual models.

## Included topics

- Bubble sort
- Insertion sort
- Selection sort
- Merge sort
- Quick sort
- Binary search
- Recursive binary search
- Linear search
- Stack using array
- Stack using linked list
- Queue using array
- Queue using linked list
- Circular queue using linked list

## Features

- Play, pause, step forward/backward, and reset animations
- Change or shuffle input values
- Per-step explanation and live counters
- Definitions, practical applications, complexity notes, and pseudocode
- Search/filter by topic
- Complexity comparison table
- Responsive layout and light/dark theme toggle
- No frameworks, packages, API keys, or build step required

## Run locally

Open `index.html` in a modern browser. Everything runs client-side.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `algorithm-visual-lab`.
2. Extract this ZIP and upload **the contents of this folder** to the repository root. The root must contain `index.html`, `styles.css`, and `script.js`.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for the Pages deployment to finish. The site URL will look like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

If the repository is named `YOUR-USERNAME.github.io`, the site can be published at the root URL `https://YOUR-USERNAME.github.io/`.

## Files

- `index.html` — page structure and content regions
- `styles.css` — responsive styling and theme variables
- `script.js` — topic data, visual step generation, animation controls, and complexity reference

## Notes

- This is an educational visual model, not a production benchmarking tool.
- Complexity figures describe standard implementations; implementation choices can change details. For example, an ordinary linear array queue that shifts values on dequeue is O(n), while a circular-array queue is O(1) per operation.
- Binary search topics use sorted input; linear search does not require sorted input.
