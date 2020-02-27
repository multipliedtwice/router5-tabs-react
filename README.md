# router5-tabs-react

<img src="public/banner-01.jpg" alt="React tabs component download" width="100%">

> Tabs component, based on router5 and react which provides minimalistic interface for toggleable tabbed navigation.

[![NPM](https://img.shields.io/npm/v/router5-tabs.svg)](https://www.npmjs.com/package/router5-tabs) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) ![npm](https://img.shields.io/npm/dm/@thousandsofraccoons/router5-tabs-react)

## Install

```bash
yarn add router5-tabs-react
```

## Features

:paperclip: Accessibility and semantics  
:earth_asia: Translation support  
:hamster: Tiny component (< 120 lines, ~3kb gzipped)  
:scissors: Customizable icons  
:heart: Tailwind default styles  
:chart_with_upwards_trend: Content won't be deleted - only hidden  
:mag: Provides data-cy prop for e2e testing

## Usage

```tsx
import Tabs from 'router5-tabs-react'

export const Profile = () => {
  return (
    <Tabs>
      <User />
      <Settings />
      <Billing />
    </Tabs>
  )
}
```

## License

MIT © [https://github.com/thousandsofraccoons](https://github.com/thousandsofraccoons)
