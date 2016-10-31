# qairoe-app-router

It's a simple routing system that changes the viewport depending on the route given

## Installation

To include this, type:

```
$ bower install littleqairoes/qairoe-app-router
```

## Usage

To use:

```html
<qairoe-app-router parent-tag-name="custom-app-shell">
  <page-element-one route="/page"></page-element-one>
  <page-element-two route="/page/:id"></page-element-two>
  <page-element-three route="/page/:id/edit" auth></page-element-three>
  <page-element-four route="/page/:id/edit" auth="[[someBooleanValue]]"></page-element-four>
  <page-not-authorized not-authorized></page-not-authorized>
  <page-not-found not-found></page-not-found>
</qairoe-app-router>
```

## Roadmap

See [ROADMAP](/ROADMAP.md)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

- v0.0.1: Changed the whole behavior to follow what I've learned from @paullewis' router used in Supercharged

- v0.0.0: Creation of repository and copying of reach-core-route element


## Credits

Toni-Jan Keith Monserrat created this for his projects.

## License

See [LICENSE](/LICENSE)