# fourty5
#/usr/share/themes/Yaru/gtk-3.20/gtk.css
@import url("resource:///com/ubuntu/themes/Yaru/3.20/gtk.css");
@import url("/apps/nautilus.css");

.nautilus-window notebook > stack {
    background-image: linear-gradient(to bottom, #e9e9e9, rgba(228, 202, 220, 0.26));
}

toolbar headerbar menu,
.primary-toolbar button menu,
headerbar button menu,
menu {
    background-image: none;
    background-image: linear-gradient(to bottom, #323030, #5e0c46);
    border-bottom-color: shade (#5e0c46, 0.8);
    border-left-color: shade (#5e0c46, 0.8);
    border-right-color: shade (#5e0c46, 0.8);
    border-top-color: #5e0c46;
    padding: 0;
    border-width: 1px;
    border-style: solid;
    padding-top: 5px;

    color: white;

    box-shadow: inset 0 1px shade (#2e2e2e, 1.18),
                inset 0 -1px shade (#2e2e2e, 1.18),
                inset -1px 0 shade (#2e2e2e, 1.16),
                inset 1px 0 shade (#2e2e2e, 1.18);

    margin: 1px;
    font-family: 'Roboto', sans-serif;

}


popover modelbutton:hover,
popover menuitem:checked:hover,
menuitem:hover,
menu menuitem:hover {
    border-radius: 0;
    background-color: rgba(204, 100, 133, 0.3);
    color: white;
}







/* Nautilus */
.nautilus-window  .titlebar{
    background: url('header-1.jpg');
    background-size: cover;
}
.nautilus-window placessidebar.sidebar, 
.nautilus-window.maximized placessidebar.sidebar{
    background-image: linear-gradient(to bottom, #323030, #5e0c46);
    color: white;
    border-right: rgba(112, 0, 19, 0.507) outset 5px;
    padding-right: 0%;
}
.nautilus-window placessidebar.sidebar row.sidebar-row,
.nautilus-window placessidebar.sidebar row.sidebar-row .sidebar-icon{
    color: white;
}
.nautilus-window placessidebar.sidebar row.sidebar-row:selected:backdrop{
    background: rgba(204, 100, 133, 0.3);
}
.nautilus-window placessidebar.sidebar row.sidebar-row:selected{
    background-color: rgba(204, 100, 133, 0.3);
}
.nautilus-window placessidebar.sidebar row.sidebar-row:hover{
    background-color: rgba(204, 100, 133, 0.2);
}

 /* same as childrens vertical margins for nicer proportions */
headerbar {
    min-height: 38px;
    padding-left: 2px;
    padding-right: 2px;
}
/* same as headerbar side padding for nicer proportions */
headerbar entry, 
headerbar spinbutton,
headerbar button,
headerbar separator {
    margin-top: 2px; 
    margin-bottom: 2px;
}
/* let the entry and button drive the titlebar size */ 
.default-decoration {
    min-height: 0; 
    padding: 0px
}


/* .nautilus-window .path-bar-box width-maximized{
    background: radial-gradient(to bottom, #323030, #5e0c46);
    border-radius: 3px;
  } */

  /* Sidebar */

/* .sidebar-row:selected {
    background: linear-gradient(
        to bottom,
        shade(@theme_bg_color, 0.85),
        shade(@theme_bg_color, 0.93) 3px,
        shade(@theme_bg_color, 0.93));
        color:#323030;
}

.sidebar-row:selected,
.sidebar-row:selected label {
    color: shade(@theme_fg_color, 0.4);
}
.sidebar-row:selected,
.sidebar-row:selected icons {
    color: shade(@theme_fg_color, 0.4);
}


.sidebar-row:selected:backdrop {
    background: linear-gradient(
        to bottom,
        shade(@theme_bg_color, 0.95),
        shade(@theme_bg_color, 0.95) 3px,
        shade(@theme_bg_color, 0.95));
}

.sidebar-row:selected:backdrop,
.sidebar-row:selected:backdrop label {
    color: shade(@theme_unfocused_fg_color, 0.85);
} */

