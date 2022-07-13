# tips

ng add @angular/material
- Angular material
- Component Dev Kit (CDK)
- Angular Animations

ng g m shared\material --dry-run --flat

ng g m demo\demo --dry-run --flat --routing
ng g c demo\buttons --dry-run --skip-tests --inline-style --inline-template
ng g c demo\flexbox  --skip-tests 

ng s -o

npm i -s @angular/flex-layout

ng g m contactmanager --dry-run

ng g c contactmanager\contactmanager-app --dry-run --flat --skip-tests --inline-style --inline-template
ng g c contactmanager\components\toolbar --skip-tests
ng g c contactmanager\components\main-content --skip-tests
ng g c contactmanager\components\sidenav --skip-tests


ng g s contactmanager\services\user  --dry-run --skip-tests

ng g class contactmanager\models\user  --dry-run --skip-tests
ng g class contactmanager\models\note  --dry-run --skip-tests