# Angular Material Timepicker

## Timepicker Control for Angular Material

⚠️The time picker control has [Angular Material](https://material.angular.io/) as a dependency ⚠️

### Usage
```html
<mat-timepicker></mat-timepicker>
```

### Component Configuration
```typescript
/** Override the label of the ok button. */
@Input() okLabel = 'Ok';

/** Override the label of the cancel button. */
@Input() cancelLabel = 'Cancel';

/** Sets the clock mode, 12-hour or 24-hour clocks are supported. */
@Input() mode = '24h' // or '12h';

@Input() disabled = false;

@Input() color = 'primary';
```

### Check out the [**Demo**](https://stackblitz.com/github/IliaIdakiev/angular-material-timepicker)!

---

Dialog View

Here's our logo (hover to see the title text):

Hour Select (24h): 
![alt text](https://github.com/IliaIdakiev/angular-material-timepicker/blob/master/timepicker-hours.png?raw=true "Hour Select (24h)")

Minutes Select: 
![alt text](https://github.com/IliaIdakiev/angular-material-timepicker/blob/master/timepicker-min.png?raw=true "Hour Select (24h)")
