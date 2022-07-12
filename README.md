# Rescript-React-snippet
a shorthand snippets for rescript-react

following snippets are supported: 

---

### `rcm` : Rescript react Component Module

```rescript
module $1 = {
  @react.component
  let make = ($2) => {
    $3
  }
} 
```

---

### `flc` : File Level Component 

```rescript
@react.component
let make = ($1) => {
  $2
}
```

---

### `rqm` : Rescript react relay Query Module

```rescript
module Query = %relay(`
  query $1 ($2) {
    $3
  }
`)
```

---

### `rmm` : Rescript react relay Mutation Module

```rescript
module Mutation = %relay(`
  mutation $1 ($2) {
    $3
  }
`)
```

### `twc` : Rescript react Tailwind classname

```rescript
className=%twc(\"$1\")
```

### `rrs` : Rescript React String

```rescript
{`${1:string}`->React.string}
```