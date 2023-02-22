# A Moment About Plugins

## What they do

- `json`: modify parsed json structure
- `code`: modify string output before or after prettier

## Lifecycle

- mitosis parser into json
- plugins: `json.pre`
- plugins: `json.post`
- target generator (react/vue/etc) (a string builder)
- plugins: `code.pre` (string)
- prettier: if enabled for target
- plugins: `code.post` (string)

<div class="notes">
I might want to create a graphic for this.
</div>
