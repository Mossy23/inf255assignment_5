How to Run

1. Clone the repository.
2. Open the project folder in the terminal.
3. Run npm install.
4. Run npm run dev.
5. Open the localhost link in your browser.
   Features

- View all animals.
- Filter by available or adopted.
- Sort by name, age, or original order.
- Adopt and return animals.
- See the number of available animals.
  Components
- App.vue: Holds the animal data and handles changes.
- AnimalCard.vue: Displays each animal and its adoption button.
- AnimalControls.vue: Contains the filter buttons and sorting menu.
  Props and Events
  Props pass information from App.vue to the other components. Events send information back to App.vue when someone clicks a button or changes a filter.
  How a Click Works
  When someone clicks Adopt, AnimalCard.vue sends an event to App.vue. App.vue changes the animal's adoption status, and Vue automatically updates the page.
  What I Learned
  I learned how to use Vue components, props, events, and computed properties. I also got more practice organizing code and making a website update automatically.


(I am not sure what I did wrong in cloning or dowloading the files but I was able to get the npm files in this exact repo.) I was having trouble with that. But I did successfully run it and can show you in class if needed. 

