## About

Angular UI library that simplifies grouping and displaying form elements. With a lightweight and customizable design, this library improves the usability and accessibility of your forms.

## Usage

Install `@ngx-tc/form-group` in your project:

```
npm install @ngx-tc/form-group
```

Import `TcFormGroupModule` e.g. in your `app.module.ts`:
```typescript
import { TcFormGroupModule } from '@ngx-tc/form-group';

@NgModule({
  imports: [
    ...
    TcFormGroupModule
  ],
})
export class AppModule {}
```

Use the `tc-form-group` component in you app:
```html
<tc-form-group>
  <tc-form-label>Form control label</tc-form-label>

  <tc-input [placeholder]="'Placeholder'"></tc-input>

  <tc-form-description>Form control description</tc-form-description>
</tc-form-group>
```

## Demo
To view a working demo of the library in action, please follow the provided link. The demo will allow you to explore the various components and features included in this library and see how they can be used in your Angular applications.
[http://tc-library.type-code.pro/#/components/inputs](http://tc-library.type-code.pro/#/components/inputs)
