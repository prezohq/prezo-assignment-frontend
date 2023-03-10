# prezo-assignment-frontend

Hi there, thanks for your interest in [Prezo](https://prezo.ai). We are excited to work with builders and hackers to help us shape Prezo.

One of the things we built into Prezo is a drag and drop component for reordering slides. Your mission, should you choose to accept it, is to create a working version of such a component.

This is what it will look like when ready [Demo video] (https://www.loom.com/share/be346974201f450f9dc7e62480ce83e6)

## Requirements
This is the slides array

```
slides = [
  {
    id: '1',
    title: 'Slide 1',
  },
  {
    id: '2',
    title: 'Slide 2',
  },
  {
    id: '3',
    title: 'Slide 3',
  },
  {
    id: '4',
    title: 'Slide 4',
  },
  {
    id: '5',
    title: 'Slide 5',
  },
  {
    id: '6',
    title: 'Slide 6',
  },
  {
    id: '7',
    title: 'Slide 7',
  },
  {
    id: '8',
    title: 'Slide 8',
  },
  {
    id: '9',
    title: 'Slide 9',
  },
  {
    id: '10',
    title: 'Slide 10',
  },
]
```

Other specs

```
slide component height = 130px
container that holds all slides -> height = 80vh

container has overflow: scroll to be able to scroll and see all slides
```

If you want a quick reference for css, look at this [repo](https://github.com/prezohq/prezo-assignment)

### Tasks
- get the drag and drop working
  - add a temporary marker above or below a slide as you drag - the marker denotes where the new slide will be placed - check the video above to see what it will look like - please reach out if you have questions

- be able to scroll inside the slide container while dragging slides - this is important - we could have many slides - and may need to scroll when reordering

- make sure the dropped slide is always visible in the viewport

- allow dragging multiple slides at once (advanced - chance to show off)

- any ux flair you want to add (ideal - chance to show off)

- add undo/redo (advanced - chance to show off)

- an implementation that you think is even better (optional)


We use Vue 3 and Typescript. But you can use whatever you are comfortable with. (Vue/React/something else)

Do not use a dragging library. Please use the [HTML Drag and drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API)


## Deliverables
- Create a repo

- Add your magic

- Host it on vercel/netlify/anywhere else

- Record a short video walking us through how you crushed this, and your thought process

- Share the repo, the video and the hosted app with us

