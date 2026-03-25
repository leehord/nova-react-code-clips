# React Code Clips

## Description

This extension gives you JavaScript and TypeScript code clips for React, React Native, Redux and GraphQL.

## Clips

### Basic Methods

| Trigger | Description                                         |
| ------: | --------------------------------------------------- |
|  `imp→` | `import moduleName from 'module'`                   |
|  `imn→` | `import 'module'`                                   |
|  `imd→` | `import { destructuredModule } from 'module'`       |
|  `ime→` | `import * as alias from 'module'`                   |
|  `ima→` | `import { originalName as aliasName} from 'module'` |
|  `exp→` | `export default moduleName`                         |
|  `exd→` | `export { destructuredModule } from 'module'`       |
|  `exa→` | `export { originalName as aliasName} from 'module'` |
|  `enf→` | `export const functionName = (params) => { }`       |
|  `edf→` | `export default (params) => { }`                    |
|  `met→` | `methodName = (params) => { }`                      |
|  `fre→` | `arrayName.forEach(element => { }`                  |
|  `fof→` | `for(let itemName of objectName { }`                |
|  `fin→` | `for(let itemName in objectName { }`                |
| `anfn→` | `(params) => { }`                                   |
|  `nfn→` | `const functionName = (params) => { }`              |
|  `dob→` | `const {propName} = objectToDescruct`               |
|  `dar→` | `const [propName] = arrayToDescruct`                |
|  `sti→` | `setInterval(() => { }, intervalTime`               |
|  `sto→` | `setTimeout(() => { }, delayTime`                   |
| `prom→` | `return new Promise((resolve, reject) => { }`       |

### React

|     Trigger | Description                                                                         |
| ----------: | ----------------------------------------------------------------------------------- |
|      `imr→` | `import React from 'react'`                                                         |
|     `imrd→` | `import ReactDOM from 'react-dom/client'`                                           |
|    `croot→` | `import { createRoot } from 'react-dom/client'`                                     |
|     `imrc→` | `import React, { Component } from 'react'`                                          |
|    `imrcp→` | `import React, { Component } from 'react' & import PropTypes from 'prop-types'`     |
|    `imrpc→` | `import React, { PureComponent } from 'react'`                                      |
|   `imrpcp→` | `import React, { PureComponent } from 'react' & import PropTypes from 'prop-types'` |
|     `imrm→` | `import { memo } from 'react'`                                                      |
|    `imrmp→` | `import { memo } from 'react' & import PropTypes from 'prop-types'`                 |
|     `impt→` | `import PropTypes from 'prop-types'`                                                |
|     `imrr→` | `import { BrowserRouter as Router, Routes, Route, NavLink } from 'react-router-dom'` |
|     `imbr→` | `import { BrowserRouter as Router } from 'react-router-dom'`                          |
|    `imbrc→` | `import { Routes, Route, NavLink, Link, Outlet } from 'react-router-dom'`             |
|    `imbrr→` | `import { Route } from 'react-router-dom'`                                            |
|    `imbrs→` | `import { Routes } from 'react-router-dom'`                                           |
|    `imbrl→` | `import { Link } from 'react-router-dom'`                                             |
|   `imbrnl→` | `import { NavLink } from 'react-router-dom'`                                          |
|    `imbro→` | `import { Outlet } from 'react-router-dom'`                                           |
|   `imbrna→` | `import { Navigate } from 'react-router-dom'`                                         |
|   `imrnav→` | `import { useNavigate } from 'react-router-dom'`                                      |
|   `imrpar→` | `import { useParams } from 'react-router-dom'`                                        |
|   `imrloc→` | `import { useLocation } from 'react-router-dom'`                                      |
|    `imrsp→` | `import { useSearchParams } from 'react-router-dom'`                                  |
|     `imrs→` | `import { useState } from 'react'`                                                  |
|    `imrse→` | `import { useState, useEffect } from 'react'`                                       |
|    `redux→` | `import { connect } from 'react-redux'`                                             |
| `rcontext→` | `const ${1:contextName} = createContext()`                                          |
|     `fref→` | `React.forwardRef((props, ref) => element)`                                         |

### React Native

|    Trigger | Description                            |
| ---------: | -------------------------------------- |
|    `imrn→` | `import { $1 } from 'react-native'`    |
| `rnstyle→` | `const styles = StyleSheet.create({})` |

### Redux

|      Trigger | Description               |
| -----------: | ------------------------- |
|  `rxaction→` | `redux action template`   |
|   `rxconst→` | `export const $1 = '$1'`  |
| `rxreducer→` | `redux reducer template`  |
|  `rxselect→` | `redux selector template` |
|   `rxslice→` | `redux slice template`    |

### PropTypes

|   Trigger | Description                              |
| --------: | ---------------------------------------- |
|    `pta→` | `PropTypes.array`                        |
|   `ptar→` | `PropTypes.array.isRequired`             |
|    `ptb→` | `PropTypes.bool`                         |
|   `ptbr→` | `PropTypes.bool.isRequired`              |
|    `ptf→` | `PropTypes.func`                         |
|   `ptfr→` | `PropTypes.func.isRequired`              |
|    `ptn→` | `PropTypes.number`                       |
|   `ptnr→` | `PropTypes.number.isRequired`            |
|    `pto→` | `PropTypes.object`                       |
|   `ptor→` | `PropTypes.object.isRequired`            |
|    `pts→` | `PropTypes.string`                       |
|   `ptsr→` | `PropTypes.string.isRequired`            |
|   `ptnd→` | `PropTypes.node`                         |
|  `ptndr→` | `PropTypes.node.isRequired`              |
|   `ptel→` | `PropTypes.element`                      |
|  `ptelr→` | `PropTypes.element.isRequired`           |
|    `pti→` | `PropTypes.instanceOf(name)`             |
|   `ptir→` | `PropTypes.instanceOf(name).isRequired`  |
|    `pte→` | `PropTypes.oneOf([name])`                |
|   `pter→` | `PropTypes.oneOf([name]).isRequired`     |
|   `ptet→` | `PropTypes.oneOfType([name])`            |
|  `ptetr→` | `PropTypes.oneOfType([name]).isRequired` |
|   `ptao→` | `PropTypes.arrayOf(name)`                |
|  `ptaor→` | `PropTypes.arrayOf(name).isRequired`     |
|   `ptoo→` | `PropTypes.objectOf(name)`               |
|  `ptoor→` | `PropTypes.objectOf(name).isRequired`    |
|   `ptsh→` | `PropTypes.shape({ })`                   |
|  `ptshr→` | `PropTypes.shape({ }).isRequired`        |
|  `ptany→` | `PropTypes.any`                          |
| `ptypes→` | `static propTypes = {}`                  |

### GraphQL

> Uses `@apollo/client` hooks. Install with `npm install @apollo/client graphql`.

|    Trigger | Description                                                   |
| ---------: | ------------------------------------------------------------- |
| `graphql→` | `import { useQuery, useMutation, gql } from '@apollo/client'` |
|  `expgql→` | `useQuery(QUERY, { variables: { } })`                         |

### Console

| Trigger | Description                         |
|  -----: | ----------------------------------- |
|  `clg→` | `console.log(object)`               |
|  `clo→` | ```console.log(`object`, object)``` |
|  `ctm→` | ```console.time(`timeId`)```        |
|  `cte→` | ```console.timeEnd(`timeId`)```     |
|  `cas→` | `console.assert(expression,object)` |
|  `ccl→` | `console.clear()`                   |
|  `cco→` | `console.count(label)`              |
|  `cdi→` | `console.dir`                       |
|  `cer→` | `console.error(object)`             |
|  `cgr→` | `console.group(label)`              |
|  `cge→` | `console.groupEnd()`                |
|  `ctr→` | `console.trace(object)`             |
|  `cwa→` | `console.warn`                      |
|  `cin→` | `console.info`                      |

### React Components

#### `rfcp`

```javascript
import PropTypes from 'prop-types'

function $1(props) {
  return <div>$0</div>
}

$1.propTypes = {}

export default $1
```

#### `rfc`

```javascript
export default function $1() {
  return <div>$0</div>
}
```

#### `rfce`

```javascript
function $1() {
  return <div>$0</div>
}

export default $1
```

#### `rafcp`

```javascript
import PropTypes from 'prop-types'

const $1 = (props) => {
  return <div>$0</div>
}

$1.propTypes = {}

export default $1
```

#### `rafc`

```javascript
export const $1 = () => {
  return <div>$0</div>
}
```

#### `rafce`

```javascript
const $1 = () => {
  return <div>$0</div>
}

export default $1
```

#### `rmc`

```javascript
import { memo } from 'react'

export default memo(function $1() {
  return <div>$0</div>
})
```

#### `rmcp`

```javascript
import { memo } from 'react'
import PropTypes from 'prop-types'

const $1 = memo(function $1(props) {
  return <div>$0</div>
})

$1.propTypes = {}

export default $1
```

#### `rfcredux`

```javascript
import { connect } from 'react-redux'

export const FileName = () => {
  return <div>$4</div>
}

const mapStateToProps = (state) => ({})

const mapDispatchToProps = {}

export default connect(mapStateToProps, mapDispatchToProps)(FileName)
```

#### `rfcreduxp`

```javascript
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

export const FileName = () => {
  return <div>$4</div>
}

FileName.propTypes = {
  $2: $3,
}

const mapStateToProps = (state) => ({})

const mapDispatchToProps = {}

export default connect(mapStateToProps, mapDispatchToProps)(FileName)
```

#### `reduxmap`

```javascript
const mapStateToProps = (state) => ({})

const mapDispatchToProps = {}
```

#### `reb`

```javascript
import { Component } from 'react'

class ErrorBoundary extends Component {
  constructor(props) {
    super(props)
    this.state = { hasError: false }
  }

  static getDerivedStateFromError(error) {
    return { hasError: true }
  }

  componentDidCatch(error, errorInfo) {
    console.error(error, errorInfo)
  }

  render() {
    if (this.state.hasError) {
      return <h1>Something went wrong.</h1>
    }
    return this.props.children
  }
}

export default ErrorBoundary
```

#### `rlazy`

```javascript
const Component = lazy(() => import('./Component'))
```

#### `rsuspense`

```javascript
import { Suspense, lazy } from 'react'

const Component = lazy(() => import('./Component'))

export default function Parent() {
  return (
    <Suspense fallback={<div>Loading...</div>}>
      <Component />
    </Suspense>
  )
}
```

### React Native Components

#### `rnf`

```javascript
import { View, Text } from 'react-native'

export default function $1() {
  return (
    <View>
      <Text> $2 </Text>
    </View>
  )
}
```

#### `rnfs`

```javascript
import { StyleSheet, View, Text } from 'react-native'

export default function $1() {
  return (
    <View>
      <Text> $2 </Text>
    </View>
  )
}

const styles = StyleSheet.create({})
```

#### `rnfe`

```javascript
import { View, Text } from 'react-native'

const $1 = () => {
  return (
    <View>
      <Text> $2 </Text>
    </View>
  )
}

export default $1
```

#### `rnfes`

```javascript
import { StyleSheet, View, Text } from 'react-native'

const $1 = () => {
  return (
    <View>
      <Text> $2 </Text>
    </View>
  )
}

export default $1

const styles = StyleSheet.create({})
```

> TypeScript variants of the above components can be accessed by using the `ts` prefix e.g. `tsrfce`

### TanStack Query

> Install with `npm install @tanstack/react-query`.

|        Trigger | Description                                            |
| -------------: | ------------------------------------------------------ |
| `tqprovider→` | `QueryClientProvider` app setup                        |
|      `imtq→` | `import { useQuery, useMutation, useQueryClient }`      |
|   `tqquery→` | `useQuery({ queryKey, queryFn })`                       |
| `tqmutation→` | `useMutation({ mutationFn, onSuccess })`                |

#### `tqprovider`

```javascript
import { QueryClient, QueryClientProvider } from '@tanstack/react-query'

const queryClient = new QueryClient()

export default function App() {
  return (
    <QueryClientProvider client={queryClient}>
      children
    </QueryClientProvider>
  )
}
```

#### `tqquery`

```javascript
const { data, isLoading, error } = useQuery({
  queryKey: ['key'],
  queryFn: fetchFn
})
```

#### `tqmutation`

```javascript
const mutation = useMutation({
  mutationFn: mutateFn,
  onSuccess: () => {
    queryClient.invalidateQueries({ queryKey: ['key'] })
  }
})
```

### SWR

> Install with `npm install swr`.

|   Trigger | Description                        |
| --------: | ---------------------------------- |
| `imswr→` | `import useSWR from 'swr'`         |
|   `swr→` | `useSWR(key, fetcher)`             |
|  `swrf→` | `useSWR` with inline async fetcher |

#### `swr`

```javascript
const { data, error, isLoading } = useSWR('key', fetcher)
```

#### `swrf`

```javascript
const { data, error, isLoading } = useSWR(
  'key',
  async (url) => {
    const res = await fetch(url)
    return res.json()
  }
)
```

### Other

#### `cmmb`

```JS
/**
|--------------------------------------------------
| $1
|--------------------------------------------------
*/
```

#### `desc`

```javascript
describe('$1', () => {
  $2
})
```

#### `test`

```javascript
test('should $1', () => {
  $2
})
```

#### `tit`

```javascript
it('should $1', () => {
  $2
})
```

#### `stest`

```javascript
import { render, screen } from '@testing-library/react'

import { ${1:ComponentName} } from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}

  test('render', () => {
    render(<${1:ComponentName} {...defaultProps} />)
    expect(screen.getByRole('$2')).toBeInTheDocument()
  })
})
```

#### `srtest`

```javascript
import { render, screen } from '@testing-library/react'
import { Provider } from 'react-redux'

import store from 'src/store'
import { ${1:ComponentName} } from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}

  test('render', () => {
    render(
      <Provider store={store}>
        <${1:ComponentName} {...defaultProps} />
      </Provider>,
    )
    expect(screen.getByRole('$2')).toBeInTheDocument()
  })
})
```

#### `sntest`

```javascript
import { render, screen } from '@testing-library/react-native'

import ${1:ComponentName} from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}

  test('render', () => {
    render(<${1:ComponentName} {...defaultProps} />)
    expect(screen.getByText('$2')).toBeTruthy()
  })
})
```

#### `snrtest`

```javascript
import { render, screen } from '@testing-library/react-native'
import { Provider } from 'react-redux'

import store from 'src/store/configureStore'
import ${1:ComponentName} from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}

  test('render', () => {
    render(
      <Provider store={store}>
        <${1:ComponentName} {...defaultProps} />
      </Provider>,
    )
    expect(screen.getByText('$2')).toBeTruthy()
  })
})
```

#### `hocredux`

```javascript
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

export const mapStateToProps = state => ({

})

export const mapDispatchToProps = {

}

export const ${1:hocComponentName} = (WrappedComponent) => {
  const hocComponent = ({ ...props }) => <WrappedComponent {...props} />

  hocComponent.propTypes = {
  }

  return hocComponent
}

export default WrapperComponent => connect(mapStateToProps, mapDispatchToProps)(${1:hocComponentName}(WrapperComponent))
```

#### `hoc`

```javascript
import PropTypes from 'prop-types'

export default (WrappedComponent) => {
  const hocComponent = ({ ...props }) => <WrappedComponent {...props} />

  hocComponent.propTypes = {}

  return hocComponent
}
```

#### `useId`

```javascript
const id = useId()
```

#### `useSyncExternalStore`

```javascript
const snapshot = useSyncExternalStore(subscribe, getSnapshot)
```

#### `useInsertionEffect`

```javascript
useInsertionEffect(() => {
  effect
  return () => {
    cleanup
  }
}, [input])
```

#### `useHook` *(React 19 — `use()`)*

```javascript
const value = use(resource)
```

#### `useOptimistic`

```javascript
const [optimisticState, addOptimistic] = useOptimistic(state)
```

#### `useActionState`

```javascript
const [state, formAction, isPending] = useActionState(action, initialState)
```

#### `useFormStatus`

```javascript
const { pending, data, method, action } = useFormStatus()
```

#### `useNavigate`

```javascript
const navigate = useNavigate()
```

#### `useParams`

```javascript
const { param } = useParams()
```

#### `useLocation`

```javascript
const location = useLocation()
```

#### `useSearchParams`

```javascript
const [searchParams, setSearchParams] = useSearchParams()
```

#### `useTransition`

```javascript
const [isPending, startTransition] = useTransition()
```

#### `useDeferredValue`

```javascript
const deferredValue = useDeferredValue(value)
```

#### `useState`

```javascript
const [state, setState] = useState(initialState)
```

#### `useEffect`

```javascript
useEffect(() => {
  effect
  return () => {
    cleanup
  }
}, [input])
```

#### `useContext`

```javascript
const context = useContext(contextValue)
```

#### `useReducer`

```javascript
const [state, dispatch] = useReducer(reducer, initialState, init)
```

#### `useCallback`

```javascript
const ${1:memoizedFn} = useCallback(
  () => {
    ${2:callback}
  },
  [${3:deps}],
)
```

#### `useMemo`

```javascript
const ${1:memoizedValue} = useMemo(() => ${2:computeFn}, [${3:deps}])
```

#### `useRef`

```javascript
const ref = useRef(initialValue)
```

#### `useImperativeHandle`

```javascript
useImperativeHandle(
  ref,
  () => {
    handler
  },
  [input],
)
```

#### `useDebugValue`

```javascript
useDebugValue(value)
```

#### `useLayoutEffect`

```javascript
useLayoutEffect(() => {
  effect
  return () => {
    cleanup
  };
}, [input])
```

#### `useSelector`

```javascript
const state = useSelector(state => state.state)
```

#### `useDispatch`

```javascript
const dispatch = useDispatch()
```

## Acknowledgements

React Code Clips is based on [Damian Sznajder's VS Code extension](https://github.com/dsznajder/vscode-es7-javascript-react-snippets)

## License

The MIT License (MIT)

Copyright (c) 2014, Nicolas Mercier

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.