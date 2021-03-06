# Albe Timeline <sup>1.0.0</sup>

![coming-soon](https://user-images.githubusercontent.com/24717256/48868632-62fcb600-edc1-11e8-8d84-d66289a517f4.png)

- Content HTML structure is highly manipulable.
- Styles for the template are easily customizable.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.1

## Installation
```html
$ npm install ngx-timeline-albe
```

## Usage
### Import the module
```typescript
import { NgxTimelineAlbeModule } from 'ngx-timeline-albe';

@NgModule({
    imports: [ NgxTimelineAlbeModule ],
    ...
})
export class AppModule {}
```

### Template
```html
<ngx-timeline></ngx-timeline>
```

## Demo App
Follow these instructions to run the demo:

1. Clone the repository to your local machine
2. From the project folder, run `npm i` to install all required dependencies
3. Run `ng b ngx-timeline-albe` to build in **dist** folder.
4. Run `ng s` to serve the project from a live-updating server.
5. Go to `localhost:4200` to see the demo site


## To do
- [ ] Se for passado 'string', converter para 'object'.
- [ ] Exibe mensagem padão.
- [ ] Inserir animação.
- [x] Ordenar itens pela data.

>Inspired on the plug-in: https://github.com/Albejr/jquery-albe-timeline
