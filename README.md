# Dog Poster Generator
## Directions
Write a react app (create-react-app is fine as a scaffold, or whatever generator you want), that meets the following criteria:

## Functionality - Dog Poster Generator:

Be able to specify 1-N breed/sub-breed combinations, and a count for each combo, then click a 'generate' button to display a modal containing the requested images tiled in a grid, randomly sorted.

| Breed | Sub-breed | Image Count | Action |
| --- | --- | --- | ---: |
| v Breed Dropdown v | v Sub-breed Dropdown v |  # of images | 
| v Breed Dropdown v | v Sub-breed Dropdown v |  # of images | + <-- click plus to add a row

## Technical requirements:

1. Use [Material UI](https://material-ui.com/) for the UI components
2. Use the [Stanford Dog API](https://dog.ceo/dog-api/documentation/) for data, INCLUDING dropdown population 
3. Use a least one [Higher Order Component](https://reactjs.org/docs/higher-order-components.html)
4. Provide Jest specs for at least one component in the app

- Use Typescript
- Use Suspense
- Use a custom theme
- 80% test coverage
- Use global state via redux - data down, events up (Required if applying for senior-level position)
