# aui-vue-decorator
Typescript Decorator For Vue In Agree Selfservice

***

## inatall

### yarn
    yarn add aui-vue-decorator

### npm
    npm install -g aui-vue-decorator

***

## Getting Started

### @Data
provide decorator @Data

The data object for the Vue instance
    
    import { Data } from "aui-vue-decorator"

    @Data foo: string = "foo"
    @Data bar: string = "bar"


### @FromDm (unfinished)
provide decorator @FromDm 

The data object map from dm for the Vue instance

    import { Data, FromDm } from "aui-vue-decorator"

    @Data @FromDm foo: string
    @Data @FromDm bar: string