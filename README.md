# Blazor.Seo.Friendly.FlickerFree
Process to make Blazor WebAssembly flicker-free and SEO-friendly.

- Create Blazor App WebAssembly Interactive (Global)
- Implement a mechanism to detect if a request is coming from a bot or a crawler
- Make pre-render true or false based on whether the request is coming from a bot or not, and pass that as a CascadingValue value to the Routes component
- Changes related to isBot value
- Add missing AddHttpContextAccessor service registration
- Add MIT license

## Demo

![Demo](demo/Making-Blazor-WebAssembly-SEO-Friendly-and-Flicker-Free.gif)


## References
- [Code snippet: Conditional User-Agent logic with Blazor](https://codyanhorn.tech/blog/code-snippet-conditional-user-agent-logic-with-blazor)
- [Display loading progress on Blazor .NET 8 WebAssembly pre-render false](https://stackoverflow.com/questions/77476532/display-loading-progress-on-blazor-net-8-webassembly-pre-render-false)