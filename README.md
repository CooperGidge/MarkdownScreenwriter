# Markdown Screenwriter

To run: `npx eleventy --serve` and go to [http://localhost:8080](http://localhost:8080). Edit the `_src/index.md` file with your screenplay.

| Markdown | HTML | Screenplay Element | Notes |
|----------|------|--------------------|-------|
| # | `<h1>` | Transition | Is left aligned and automatically transforms text to uppercase. |
| ## | `<h2>` | Scene Heading | Is bolded and automatically transforms text to uppercase. Will include a scene number, that increments for every instance of this, in the left and right margins of the page. |
| ### | `<h3>` | Intercut | Is bolded and automatically transforms text to uppercase. |
| #### | `<h4>` | Character | Automatically transforms text to uppercase. |
| ##### | `<h5>` | Parathentical |  |
| > | `<blockquote>` | Dialogue |  |
|  | `<p>` | Description |  |