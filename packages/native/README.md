<h2 align="center">
  <img src="https://i.imgur.com/iiR9wAs.png" alt="reactivesearch" title="reactivesearch" width="200" />
  <br />
  ReactiveSearch Native
  <br />
</h2>

<p align="center" style="font-size: 1.2rem">A React Native UI components library for Elasticsearch</p>
<p align="center"><a href="https://medium.appbase.io/build-your-next-react-native-app-with-reactivesearch-ce21829f3bf5">Read the launch blog post here</a>.</p>

<hr />

[![npm version](https://badge.fury.io/js/%40appbaseio%2Freactivesearch-native.svg)](https://badge.fury.io/js/%40appbaseio%2Freactivesearch-native)
[![](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://github.com/appbaseio/reactivesearch/blob/dev/LICENSE)
[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/appbaseio/reactivesearch)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/appbaseio/reactivesearch/blob/dev/.github/CONTRIBUTING.md)

<br />

#### :rocket: Jumpstart your app development with
```
npm install @appbaseio/reactivesearch-native
```

![](https://i.imgur.com/h33Qt6A.png)

## Introduction

Gone are those days, when it used to take several weeks or months to build and ship meaningful apps. With ReactiveSearch Native, you can ship mobile apps in days and sometimes, even a few hours.

ReactiveSearch provides scaffolding to build data-driven apps. This library bundles a range of React Native UI components that are built with extendibility in mind: You can customize the backend queries, define how the components react to changes, extend the styles with theming and style injection support.

> Above all, we've kept the components API exactly the same as that of reactivesearch for web, enabling you to write once and use everywhere.

## Available Components

Currently, we support the following components:

- TextField [Doc](https://opensource.appbase.io/reactive-manual/native/components/textfield.html), [Demo](https://expo.io/@siddharthlatest/textfield)
- DataSearch [Doc](https://opensource.appbase.io/reactive-manual/native/components/datasearch.html), [Demo](https://expo.io/@siddharthlatest/datasearch)
- SingleDropdownList [Doc](https://opensource.appbase.io/reactive-manual/native/components/singledropdownlist.html), [Demo](https://expo.io/@siddharthlatest/singledropdownlist)
- SingleDropdownRange [Doc](https://opensource.appbase.io/reactive-manual/native/components/singledropdownrange.html), [Demo](https://expo.io/@siddharthlatest/singledropdownrange)
- MultiDropdownList [Doc](https://opensource.appbase.io/reactive-manual/native/components/multidropdownlist.html), [Demo](https://expo.io/@siddharthlatest/multidropdownlist)
- MultiDropdownRange [Doc](https://opensource.appbase.io/reactive-manual/native/components/multidropdownrange.html), [Demo](https://expo.io/@siddharthlatest/multidropdownrange)
- DatePicker [Doc](https://opensource.appbase.io/reactive-manual/native/components/datepicker.html), [Demo](https://expo.io/@siddharthlatest/datepicker)
- DateRange [Doc](https://opensource.appbase.io/reactive-manual/native/components/daterange.html), [Demo](https://expo.io/@siddharthlatest/daterange)
- ReactiveList [Doc](https://opensource.appbase.io/reactive-manual/native/components/reactivelist.html) 
- ReactiveComponent [Doc](https://opensource.appbase.io/reactive-manual/native/advanced/reactivecomponent.html), [Demo](https://snack.expo.io/Sy0tN0K8f)


Docs are accessible at [reactive-manual/native](https://opensource.appbase.io/reactive-manual/native). 

## Example Apps

We have published the following apps to the App Store / Playstore.

- [Booksearch on Play Store](https://play.google.com/store/apps/details?id=com.booksnative): A booksearch app showing a searchable collection of over 10k books built with ReactiveSearch.  
- [Gitxplore on Play Store](https://play.google.com/store/apps/details?id=com.appbaseio.gitxplore): A Github repository explorer app to  search over the 25k+ most popular github repos.  
- [ReactiveTodos on App Store](https://itunes.apple.com/us/app/reactivetodos/id1347926945?mt=8): A shared collaborative to-do list app to showcase the capability of Reactivesearch.

## Contributing

Please check the [contribution guide](https://github.com/appbaseio/reactivesearch/tree/dev/.github/CONTRIBUTING.md).

## Debugging

The simplest way to debug the app is using [React Native Debugger](https://github.com/jhen0409/react-native-debugger).

## Troubleshooting

If you are having trouble running your react native app and are seeing any dependency warnings, reset cache via 

```
yarn start --reset-cache
```