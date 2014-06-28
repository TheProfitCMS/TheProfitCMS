## The!ProfitCMS

Modular, DRY, KISS and almost perfect publishing platform on edge of Rails.

### Why?

Just because I dream about it.

### For whom?

For my personal purposes and my friends

### Why I do it from scratch?

Because Rails ecosystem have nothing that I want.

### How long?

From 2008. And I think, I will never stop.

### How fast?

So slow as I can. Because I do it for myself. And I want to make it well

### The!ProfitCMS Structure

1. **Public part** - set of public and open source gems, which provide different features of cms.
2. **Private part** - core, which provide basic publishing features and integrate features from gems.

### The!ProfitCMS parts

1. **Core** - Users, Social networks login, Catalogization, Publications
2. **TheRole** - Authorization module
3. **TheSortableTree** - fast tree rendering (NestedSet)
4. **TheComments** - advanced comments with threading
5. **TheStorages** - file uploading and storage
6. **TheMetas** - polymorphic SEO metatags for objects (need to be extracted from core)
7. **TheAudit** - request information collector for internal statistics and analytics
8. **TheSimpleSort** - scopes and helpers for simple sort (need to be extracted from core)
9. **ThePagination** - simple pagination helper
10. **TheSubscribers** - create and manage of subscribers
11. **TheNotification** - makes site notifications better and reusable
12. **TheStringToSlug** - I18n-based friendly_id helper
13. **TheCrop** - cropping of images
14. **TheImage** - common helpers for image manipulations
15. **TheInterpolator** - yet another simple helper for string interpolation

### License

1. The!ProfitCMS (Private part) under Commerce License
2. Public part under MIT License
