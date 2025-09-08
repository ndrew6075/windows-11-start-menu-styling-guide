# 21996 Start & Search theme for Windows 11 Start Menu Styler

This theme tries to recreate the design that the Windows 11 start menu and search menu had on early Windows 11 builds,
which included:
* Squared search box
* No search box on the start menu
* Changed 'All' to 'All apps' as it was on older Windows 11 builds
* Reverted the search icon back to the one from 22000
* 21370-22000.9-like Acrylic
* Accent color & light/dark mode support

**Author**: [Tails](https://github.com/milesprower2293)

![Screenshot](screenshot.png) \
![Screenshot](screenshot-search.png)

## Theme selection

The theme is integrated into the mod and can simply be selected from the mod's
settings:

* Open the Windows 11 Start Menu Styler mod in Windhawk.
* Go to the "Settings" tab.
* Select the theme and save the settings.

## Manual installation

The theme styles can also be imported manually. To do that, follow these steps:

* Open the Windows 11 Start Menu Styler mod in Windhawk.
* Go to the "Advanced" tab.
* Copy the content below to the text box under "Mod settings" and click "Save".

<details>
<summary>Content to import (click to expand)</summary>

```json
{
"controlStyles[0].target":"Border#TaskbarSearchBackground",
"controlStyles[0].styles[0]":"CornerRadius=4",
"controlStyles[0].styles[1]":"BorderThickness=0,0,0,0",
"controlStyles[0].styles[2]":"Height=33",
"controlStyles[0].styles[3]":"BorderBrush:=<SolidColorBrush Color=\"{ThemeResource ControlStrokeColorDefault}\"/>",
"controlStyles[1].target":"StartDocked.SearchBoxToggleButton > Grid > ContentPresenter > TextBlock#PlaceholderText",
"controlStyles[1].styles[0]":"Margin=0,0,0,2",
"controlStyles[2].target":"StartDocked.SearchBoxToggleButton#StartMenuSearchBox > Grid > Border#BorderElement",
"controlStyles[2].styles[0]":"BorderThickness=0,0,0,2",
"controlStyles[2].styles[1]":"BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight1}\"/>",
"controlStyles[3].target":"StartDocked.SearchBoxToggleButton > Grid > FontIcon > Grid > TextBlock",
"controlStyles[3].styles[0]":"Foreground:=<SolidColorBrush Color=\"gray\" />",
"controlStyles[3].styles[1]":"Margin=0,0,0,1",
"controlStyles[3].styles[2]":"Transform3D:=<CompositeTransform3D RotationY=\"180\" TranslateX=\"16\" />",
"controlStyles[4].target":"Microsoft.UI.Xaml.Controls.AnimatedIcon#SearchIconPlayer",
"controlStyles[4].styles[0]":"Visibility=1",
"controlStyles[4].styles[1]":"FlowDirection=1",
"controlStyles[4].styles[2]":"Transform3D:=<CompositeTransform3D RotationY=\"180\" TranslateX=\"16\" />",
"controlStyles[5].target":"FontIcon#SearchBoxOnTaskbarSearchGlyph",
"controlStyles[5].styles[0]":"Visibility=0",
"controlStyles[5].styles[1]":"Foreground:=<SolidColorBrush Color=\"gray\" />",
"controlStyles[5].styles[2]":"FlowDirection=1",
"controlStyles[5].styles[3]":"FontFamily=Segoe Fluent Icons",
"controlStyles[5].styles[4]":"RequestedTheme=1",
"controlStyles[5].styles[5]":"Transform3D:=<CompositeTransform3D RotationY=\"180\" TranslateX=\"23\" TranslateY=\"0.5\" />",
"controlStyles[5].styles[6]":"FontSize=17",
"controlStyles[6].target":"StartDocked.SearchBoxToggleButton#StartMenuSearchBox > Grid",
"controlStyles[6].styles[0]":"BorderBrush:=<SolidColorBrush Color=\"{ThemeResource ControlStrokeColorDefault}\"/>",
"controlStyles[6].styles[1]":"BorderThickness=1,1,1,0",
"controlStyles[6].styles[2]":"CornerRadius=4",
"controlStyles[7].target":"Cortana.UI.Views.RichSearchBoxControl#SearchBoxControl > Grid#RootGrid",
"controlStyles[7].styles[0]":"CornerRadius=4",
"controlStyles[7].styles[1]":"BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight1}\" />",
"controlStyles[7].styles[2]":"BorderThickness=2,2,2,2",
"controlStyles[7].styles[3]":"Margin=-2,-0,0,-2",
"controlStyles[8].target":"StartDocked.SearchBoxToggleButton",
"controlStyles[8].styles[0]":"CornerRadius=4",
"controlStyles[8].styles[1]":"Height=40",
"controlStyles[9].target":"Windows.UI.Xaml.Controls.Grid#SearchBoxOnTaskbarGleamContainer",
"controlStyles[9].styles[0]":"CornerRadius=4",
"controlStyles[10].target":"Windows.UI.Xaml.Controls.Grid#SearchBoxOnTaskbarGleamImageContainer",
"controlStyles[10].styles[0]":"CornerRadius=4",
"controlStyles[10].styles[1]":"Transform3D:=<CompositeTransform3D TranslateX=\"1.8\" />",
"controlStyles[11].target":"Windows.UI.Xaml.Controls.Image#SearchIconOff",
"controlStyles[11].styles[0]":"Transform3D:=<CompositeTransform3D RotationY=\"180\" TranslateX=\"16\" TranslateY=\"-1\" />",
"controlStyles[12].target":"Windows.UI.Xaml.Controls.Image#SearchIconOn",
"controlStyles[12].styles[0]":"Transform3D:=<CompositeTransform3D RotationY=\"180\" TranslateX=\"16\" TranslateY=\"-1\" />",
"controlStyles[13].target":"Windows.UI.Xaml.Controls.Button#ShowAllAppsButton > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter > Windows.UI.Xaml.Controls.StackPanel > Windows.UI.Xaml.Controls.TextBlock#ShowAllAppsButtonText",
"controlStyles[13].styles[0]":"Text=All apps",
"controlStyles[14].target":"Windows.UI.Xaml.Controls.TextBlock#AllAppsHeading",
"controlStyles[14].styles[0]":"Text=All apps",
"controlStyles[15].target":"StartDocked.SearchBoxToggleButton",
"controlStyles[15].styles[0]":"Height=0",
"controlStyles[15].styles[1]":"Margin=0,0,0,32",
"controlStyles[16].target":"StartDocked.LauncherFrame",
"controlStyles[16].styles[0]":"Height=670",
"controlStyles[17].target":"Windows.UI.Xaml.Controls.Grid#InnerContent",
"controlStyles[17].styles[0]":"Margin=0,0,0,0",
"controlStyles[18].target":"Cortana.UI.Views.HostedWebViewControl#QueryFormulationHostedWebView",
"controlStyles[18].styles[0]":"Background:=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeMediumColor}\" TintOpacity=\"1\" TintLuminosityOpacity=\"1\" FallbackColor=\"{ThemeResource SystemChromeLowColor}\" />",
"controlStyles[19].target":"Windows.UI.Xaml.Controls.Grid#QueryFormulationRoot",
"controlStyles[19].styles[0]":"CornerRadius=10",
"controlStyles[20].target":"Windows.UI.Xaml.Controls.Border#AcrylicBorder",
"controlStyles[20].styles[0]":"Opacity=0.5",
"controlStyles[21].target":"Windows.UI.Xaml.Controls.Grid#MainContent",
"controlStyles[21].styles[0]":"Background:=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeMediumColor}\" TintOpacity=\"0\" TintLuminosityOpacity=\"0.5\" FallbackColor=\"{ThemeResource SystemChromeLowColor}\" />",
"controlStyles[21].styles[1]":"CornerRadius=7",
"controlStyles[22].target":"Windows.UI.Xaml.Controls.Border#AppBorder",
"controlStyles[22].styles[0]":"Background:=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeMediumColor}\" TintOpacity=\"0\" TintLuminosityOpacity=\"0.7\" FallbackColor=\"{ThemeResource SystemChromeLowColor}\" />"
}
```
</details>

## Removing the "Recommended" section

The "Recommended" section can be removed by following these steps:

* Import [the NoRecommendedSection
  theme](https://github.com/ramensoftware/windows-11-start-menu-styling-guide/blob/main/Themes/NoRecommendedSection/README.md)
  using the **Manual installation** instructions.
* Select this theme using the **Theme selection** instructions on this page.
