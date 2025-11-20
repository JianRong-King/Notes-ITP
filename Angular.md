### Ask

1. Sample / documentation on code implementation practice
2. **Clarify if using Standalone**


1️⃣ Generate the component

Use the CLI:
ng g c <component-name> --standalone


We have created:
dashboard/
  dashboard.component.ts
  dashboard.component.html
  dashboard.component.css


## Reusability
- Property Binding
🔗 Property Binding (Data Down)
Property binding allows you to set the value of a target HTML element's or component's property directly from a property in your Angular component class

EG. 
Basic Binding	<img **[src]**="imageURL">

The syntax for property binding uses square brackets [] around the target property.

src = target (eg. property that we are changing in the DOM)
imageURL = Data truth (from .ts mostly)

parent uses [property]="data" (property binding) to send that data



<br>


- Event Binding

- Content Projection


## Component


import { Component } from '@angular/core';

@Component({
  selector: 'app-hello-world', // <-- How you use it in HTML: <app-hello-world></app-hello-world>
  templateUrl: './app.component.html', // <-- Points to the component's HTML
  styleUrls: ['./app.component.css'] // <-- Points to the component's styles
})


- @Input()
- @Output()

## Directive
- ngif
- ngSwitch etc..


## Calling the component


## Content projection


## Dependency Injection

tmr

## Services


## Routing


## Pipes












