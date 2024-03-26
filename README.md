# Blazor.Seo.Friendly.FlickerFree
Process to make Blazor WebAssembly flicker-free and SEO-friendly.

- Create Blazor App WebAssembly Interactive (Global)
- Implement a mechanism to detect if a request is coming from a bot or a crawler
- Make pre-render true or false based on whether the request is coming from a bot or not, and pass that as a CascadingValue value to the Routes component
- Changes related to isBot value
- Add missing AddHttpContextAccessor service registration
- Add MIT license