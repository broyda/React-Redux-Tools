# React-Redux-Tools

1. React Dev Tools
2. Redux Dev Tools
3. React Perf
4. Component Inspector (https://github.com/lahmatiy/component-inspector#react)
5. Component Flow Loader (https://github.com/gurdasnijor/component-flow-loader)
6. React JSON Inspector (https://github.com/Lapple/react-json-inspector)
7. React Inspector (https://github.com/xyc/react-inspector)
8. React Component Hierarchy (https://github.com/bpxl-labs/react-component-hierarchy)
9. Visible React (https://github.com/rkendall/visible-react)
10. DOM visualizer (https://github.com/roman01la/react-dom-visualizer)
11. React Lumberjack (https://github.com/ryanflorence/react-lumberjack)

# Debugging techniques
1. Blackbox scripts (if need be)
2. For a DOM node, retrieve the CSS selector
3. Edit HTML (shift-tab to rearrange)
4. Use .cls feature for live css debugging
~~~~
* Toggle checkbox(es) on and off
* Add class to that element
~~~~
5. console.trace() - stacktraces
6. Edit html in console - Select in Elements, $0 to output html, Edit attribute or Edit HTML -> Reveal
7. Search pane for methods
8. debug(fn) undebug(fn) eventListeners
9. monitor(fn) unmonitor(fn)

# Performance debugging
1. console.timeStamp()
2. console.time(Label1) and console.timeEnd(Label1) - for Label1


# JSX recipes

Comments in JSX
```
{/*
  This is a JXS comment
*/}
```

Shorthand to pass props like so:
```
<Somecomponent {...myProps} />
```

Pass multiple styles inside className like so:
const classes = ['someclass1', 'someclass2']
<div className = {classes.join(' ')} ></div>

#### CSS techniques
* {
  background: rgba(0,0,0,0.3);
}
