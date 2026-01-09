# herb-linter-custom-rule-html-content-model-conformance
https://github.com/marcoroth/herb/pull/1030

## Usage

Add 2 npm packages to `package.json`.

```
  "devDependencies": {
    "@herb-tools/linter": "^0.8.7",
    "html-content-model-conformance": "git+https://github.com/kozy4324/herb-linter-custom-rule-html-content-model-conformance.git"
  }
```

`.herb/rules/html-content-model-conformance.mjs`:

```
import { HTMLContentModelConformanceRule } from "html-content-model-conformance"
export default HTMLContentModelConformanceRule
```

## See also

https://herb-tools.dev/projects/linter#custom-rules
