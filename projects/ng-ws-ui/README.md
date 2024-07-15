# ng-ws-ui

![Angular 17](https://img.shields.io/badge/Angular%2017-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

A collection of reusable Angular 17 UI components.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage) 

## Installation

To install the entire `ng-ws-ui` package:

```bash
npm install ng-ws-ui 
```

Or, to install individual libraries:
```bash
npm install ng-ws-video-player
```

## Usage

Import the desired component in your standalone component or app.component.ts:

```typescript 
import { Component } from '@angular/core';

import { NgWsVideoPlayerComponent } from 'ng-ws-video-player';

@Component({
  selector: 'app-root',
  standalone: true,
  imports: [NgWsVideoPlayerComponent],
  template: `<ng-ws-video-player/>`
})
export class AppComponent {}
```
