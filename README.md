# angular2-practice

Angular lifecycle

Sequence:
1. constructor is called!
2. ngOnChanges called!
    - This is the only method which recevies the argument 
    ngOnChanges( changes : SimpleChanges ){
      // changes is an object which stores the value of the variable of that component. 
      // also stroes some important value like, 'FirstChange'
    }
3. ngOnInit is called!
4. ngDoCheck called! ( This is called on every changes in the component ) 
5. ngAfterContentInit called! 
    - It is called on <ng-content></ng-content>
6. ngAfterContentChecked called!
7. ngAfterViewInit called!
8. ngAfterViewChecked called!
9. ngOnDestroy called!
