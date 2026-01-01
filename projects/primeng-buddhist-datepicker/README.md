# primeng-buddhist-year-datepicker-21-unofficial

This library is a **PrimeNG v21** compatible implementation of a DatePicker with **Buddhist Year (BE)** support. It re-implements the logic from the original `primeng-buddhist-datepicker` on top of the modern PrimeNG v21 `DatePicker`.

> ✅ Built with [Angular CLI 21](https://github.com/angular/angular-cli)  
> 📦 Supports **PrimeNG 21** and **Angular 21**

---

## 🔄 Version Compatibility

| Angular Version     | Library Version                                     | Install Command                                               |
| ------------------- | --------------------------------------------------- | ------------------------------------------------------------- |
| `^21.0.0` and above | `primeng-buddhist-year-datepicker-21-unofficial@21` | `npm i primeng-buddhist-year-datepicker-21-unofficial@latest` |
| `^19.0.0` and above | `primeng-buddhist-year-datepicker@19`               | `npm i primeng-buddhist-year-datepicker@^19.0.0`              |

> ⚠️ Make sure to match the correct version of the library with your Angular version.

---

## 🧪 Run Demo App

To see the component in action:

```bash
npm install

ng build primeng-buddhist-datepicker

ng serve
```

## 🧪 Import Modules Into Component

```
import { DatePickerModule } from 'primeng-buddhist-year-datepicker';
```

## How to use

selector datepicker the same as primeng add only [isBudhistYear] = true or false

```
@Component({
  selector: 'your-component',
  standalone: true,
  imports: [DatePickerModule],
  template: `
    <p-date-picker
      [isBudhistYear]="true"
      dateFormat="dd/mm/yy"
      placeholder="Select a date"
    ></<p-date-picker>
  `
})
export class YourComponent {}
```
