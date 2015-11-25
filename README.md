# Application Layouts in ASP.NET 5 and MDL

Do you know this project?

https://github.com/PolymerElements/app-layout-templates

This project is just set of exercises on the concepts shown in linked project.

## Documentation

The goal is to have a markup like this:

```html
<mdl-drawer-panel id="drawerPanel">

  <div class="nav" drawer>
    <!-- Nav Content -->
  </div>

  <mdl-header-panel class="main" main mode="waterfall">
    <!-- Main Toolbar -->
    <mdl-toolbar>
      <mdl-icon-button icon="menu" mdl-drawer-toggle></mdl-icon-button>
    </mdl-toolbar>

    <!-- Main Content -->
    <div class="content">
      @RenderBody()
    </div>

  </mdl-header-panel>

</mdl-drawer-panel>
```

using mix of View Component and Tag Helper custom classes.

## Author
@peterblazejewicz
