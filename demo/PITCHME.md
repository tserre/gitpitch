# Try to edit
---
```elixir
    defmodule GenMetrics.GenStage.Monitor do
	use GenServer
	alias GenMetrics.GenStage.Manager
	alias GenMetrics.GenStage.Monitor
	alias GenMetrics.GenStage.Pipeline
	alias GenMetrics.GenStage.Window
	alias GenMetrics.Reporter
	alias GenMetrics.Utils.Runtime

	@moduledoc false
	@handle_demand :handle_demand
	@handle_events :handle_events
	@handle_call   :handle_call
	@handle_cast   :handle_cast

	defstruct pipeline: %Pipeline{}, metrics: nil, start: 0, duration: 0
    ```

---
## Add Some Slide Candy

![](assets/img/presentation.png)

---?color=linear-gradient(180deg, white 75%, black 25%)
@title[Customize Slide Layout]

@snap[west span-50]
## Customize the Layout
@snapend

@snap[east span-50]
![](assets/img/presentation.png)
@snapend

@snap[south span-100 text-white]
Snap Layouts let you create custom slide designs directly within your markdown.
@snapend

---?color=linear-gradient(90deg, #E27924 65%, white 35%)
@title[Add A Little Imagination]

@snap[north-west h4-white]
#### And start presenting...
@snapend

@snap[west span-55]
@ul[spaced text-white]
- You will be amazed
- What you can achieve
- *With a little imagination...*
- And **GitPitch Markdown**
@ulend
@snapend

@snap[east span-45]
@img[shadow](assets/img/conference.png)
@snapend

---?image=assets/img/presenter.jpg

@snap[north span-100 h2-white]
## Now It's Your Turn
@snapend

@snap[south span-100 text-06]
[Click here to jump straight into the interactive feature guides in the GitPitch Docs @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend
