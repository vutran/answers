# CSS

## Anonymous block containers

You can't truncate text in a [flex-item](https://drafts.csswg.org/css-flexbox/#flex-items) directly. This is because flex items are wrapped by an [anonymous block container]([ref](https://drafts.csswg.org/css-display-3/#anonymous)). You will need to wrap your content inside an element block container to apply the `text-overflow` there instead.