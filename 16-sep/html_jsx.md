### Key Syntax Differences between HTML and JSX

| Aspect | HTML | JSX |
| :--- | :--- | :--- |
| **Class Attribute** | `class="my-class"` | `className="my-class"` |
| **For Attribute** | `<label for="name">Name:</label>` | `<label htmlFor="name">Name:</label>` |
| **Inline Styling** | `style="color: red; font-size: 16px;"` | `style={{color: 'red', fontSize: '16px'}}` |
| **Event Handling** | `<button onclick="myFunction()">Click Me</button>` | `<button onClick={myFunction}>Click Me</button>` |
| **Embedding JavaScript** | Not possible | `{...}` (e.g., `{variableName}`, `{1 + 1}`, `{myFunction()}`) |
| **Self-Closing Tags** | Optional for some (e.g., `<img>`) | Required for all empty elements (e.g., `<img />`, `<br />`) |
| **Comments** | `<!-- This is a comment -->` | `{/* This is a comment */}` |
| **Boolean Attributes** | `<input checked>` | `<input checked={true} />` or just `<input checked />` |
| **Fragments** | Not applicable | `<>...</>` or `<React.Fragment>...</React.Fragment>` |
| **Reserved Keywords** | N/A | `class` and `for` are reserved, so use `className` and `htmlFor` |
| **Attribute Naming Convention** | Attributes are lowercase with hyphens (e.g., `tabindex`, `maxlength`) | CamelCase naming (e.g., `tabIndex`, `maxLength`) |
| **Case Sensitivity** | Not case-sensitive (`<DIV>` = `<div>`) | Case-sensitive (`<Div>` is a component, `<div>` is HTML element) |
| **Children Rendering** | Text is written directly between tags | Text or components can be wrapped in `{}` or as child nodes |
