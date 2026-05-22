# ANSWERS.md

## 1. How to Run

Open the `index.html` file in a browser. No commands needed.

If you want to use VS Code, install the Live Server extension and right-click `index.html` then click "Open with Live Server". It will open at `http://127.0.0.1:5500`.

---

## 2. Stack and Design Choices

I used plain HTML, CSS, and JavaScript with no frameworks. I chose this because the app is simple enough that it does not need React or any library. It keeps the code easy to read and there is nothing to install.

Two design decisions I made:

- I used four tip buttons (10%, 15%, 20%, Custom) instead of just an input field. This makes it faster to pick a common tip without typing anything. The active button turns green so you can clearly see which one is selected.

- The results section has a light green background to separate it from the inputs. This makes it easy to find the numbers at a glance without searching the page.

---

## 3. Responsive and Accessibility

On a 360px phone the layout is a single column and the inputs take full width so they are easy to tap. On a wider screen the card stays centered with a max width of 420px.

One accessibility thing I handled: all inputs have a label above them so screen readers can tell what each field is for.

One thing I skipped: I did not add keyboard shortcuts for the tip buttons. A user navigating with a keyboard has to tab to each button manually.

---

## 4. AI Usage

I used Claude (claude.ai) to help with this project.

- I asked it to write the basic structure of the tip calculator with live updates.
- It gave me a working layout with the calculation logic.
- I changed the styling to make it simpler and more readable. The original had too many colors so I simplified it to just white and green.
- I also changed the tip buttons from a grid layout to a flex row because it looked better on small screens.

---

## 5. Honest Gap

The app always shows the bill in dollars ($). If someone uses a different currency it does not work well. With more time I would add a currency selector at the top so the user can pick their currency symbol.
