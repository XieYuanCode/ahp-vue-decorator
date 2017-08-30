# ahp-vue-decorator
Typescript Decorator For Vue In Agree HTML5 Platfrom

***

## inatall

### yarn
    yarn add ahp-vue-decorator

### npm
    npm install -g ahp-vue-decorator

***

## Getting Started

### @Data
provide decorator @Data

The data object for the Vue instance
    
    import { Data } from "ahp-vue-decorator"

    @Data foo: string = "foo"
    @Data bar: string = "bar"


### @FromDm (unfinished)
provide decorator @FromDm 

The data object map from dm for the Vue instance

    import { Data, FromDm } from "ahp-vue-decorator"

    @Data @FromDm foo: string
    @Data @FromDm bar: string