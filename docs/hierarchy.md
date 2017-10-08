# React Component Hierarchy

The app will follow a standard VR component hierarchy:

File Structure:
* `Components`
  + `Scenes`
    - `Layouts`
      - `Elements`

## Functional Component hierarchy

* `Root`
  + `App`
    - `Switch` with `Routes` for all other components

## Title Scene

* `TitleScene`
  + Route: `/#/title`
  + State: none
  + Components:
    - `TitleLayout`
