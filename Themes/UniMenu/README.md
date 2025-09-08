# UniMenu theme for Windows 11 Start Menu Styler

**Author**: [VIN STAR](https://github.com/vinstartheme)

![Screenshot](screenshot.png)

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
  "controlStyles[0].target": "Windows.UI.Xaml.Controls.Grid#NoTopLevelSuggestionsText",
  "controlStyles[0].styles[0]": "Visibility=Collapsed",
  "controlStyles[1].target": "Windows.UI.Xaml.Controls.Grid#TopLevelSuggestionsContainer",
  "controlStyles[1].styles[0]": "Visibility=Collapsed",
  "controlStyles[2].target": "Windows.UI.Xaml.Controls.Grid#ShowMoreSuggestions",
  "controlStyles[2].styles[0]": "Visibility=Collapsed",
  "controlStyles[3].target": "Windows.UI.Xaml.Controls.Grid#TopLevelSuggestionsListHeader",
  "controlStyles[3].styles[0]": "Visibility=Collapsed",
  "controlStyles[4].target": "StartDocked.UserTileView",
  "controlStyles[4].styles[0]": "Visibility=Collapsed",
  "controlStyles[5].target": "StartDocked.AppListView",
  "controlStyles[5].styles[0]": "Visibility=Collapsed",
  "controlStyles[6].target": "Microsoft.UI.Xaml.Controls.PipsPager",
  "controlStyles[6].styles[0]": "Visibility=Collapsed",
  "controlStyles[7].target": "StartDocked.LauncherFrame > Grid#RootGrid > Grid#RootContent > Grid#MainContent > Grid#InnerContent > Rectangle",
  "controlStyles[7].styles[0]": "Visibility=Collapsed",
  "controlStyles[8].target": "StartDocked.StartSizingFrame",
  "controlStyles[8].styles[0]": "MaxHeight=520",
  "controlStyles[8].styles[1]": "Margin=-8,10,0,0",
  "controlStyles[9].target": "Windows.UI.Xaml.Controls.Grid#UndockedRoot",
  "controlStyles[9].styles[0]": "Margin=0,-70,0,-90",
  "controlStyles[10].target": "StartMenu.PinnedList",
  "controlStyles[10].styles[0]": "Height=375",
  "controlStyles[10].styles[1]": "Margin=13,30,-13,0",
  "controlStyles[11].target": "StartDocked.SearchBoxToggleButton",
  "controlStyles[11].styles[0]": "Width=480",
  "controlStyles[11].styles[1]": "Height=40",
  "controlStyles[11].styles[2]": "Margin=-100,0,0,30",
  "controlStyles[11].styles[3]": "Canvas.ZIndex=1",
  "controlStyles[12].target": "StartDocked.SearchBoxToggleButton > Grid > Windows.UI.Xaml.Controls.Border",
  "controlStyles[12].styles[0]": "CornerRadius=5",
  "controlStyles[12].styles[1]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\".3\" TintLuminosityOpacity=\".5\" Opacity=\"1\"/>",
  "controlStyles[13].target": "StartDocked.PowerOptionsView",
  "controlStyles[13].styles[0]": "Margin=-68,-870,0,0",
  "controlStyles[14].target": "Windows.UI.Xaml.Controls.GridView#PinnedList > Windows.UI.Xaml.Controls.Border > Windows.UI.Xaml.Controls.ScrollViewer > Windows.UI.Xaml.Controls.Border > Windows.UI.Xaml.Controls.Grid > Windows.UI.Xaml.Controls.ScrollContentPresenter > Windows.UI.Xaml.Controls.ItemsPresenter > Windows.UI.Xaml.Controls.ItemsWrapGrid > Windows.UI.Xaml.Controls.GridViewItem",
  "controlStyles[14].styles[0]": "Margin=5,10,0,0",
  "controlStyles[15].target": "StartMenu.PinnedList > Grid#Root",
  "controlStyles[15].styles[0]": "Padding=0",
  "controlStyles[16].target": "TextBlock#PinnedListHeaderText",
  "controlStyles[16].styles[0]": "Visibility=Collapsed",
  "controlStyles[17].target": "TextBlock#ShowAllAppsButtonText",
  "controlStyles[17].styles[0]": "Visibility=Collapsed",
  "controlStyles[18].target": "Button#ShowAllAppsButton",
  "controlStyles[18].styles[0]": "Margin=0,-2,30,0",
  "controlStyles[19].target": "Windows.UI.Xaml.Controls.TextBlock[Text=]",
  "controlStyles[19].styles[0]": "Text=",
  "controlStyles[19].styles[1]": "FontSize=16",
  "controlStyles[20].target": "Button#ShowAllAppsButton > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter@CommonStates",
  "controlStyles[20].styles[0]": "Width=40",
  "controlStyles[20].styles[1]": "Height=40",
  "controlStyles[20].styles[2]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\".3\" TintLuminosityOpacity=\".5\" Opacity=\"1\"/>",
  "controlStyles[20].styles[3]": "BorderBrush:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\".2\" TintLuminosityOpacity=\".3\" Opacity=\"1\"/>",
  "controlStyles[20].styles[4]": "Background@PointerOver:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\"0\" TintLuminosityOpacity=\".2\" Opacity=\"1\"/>",
  "controlStyles[21].target": "StartDocked.NavigationPaneButton#PowerButton > Grid@CommonStates > Border#BackgroundBorder",
  "controlStyles[21].styles[0]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\".3\" TintLuminosityOpacity=\".5\" Opacity=\"1\"/>",
  "controlStyles[21].styles[1]": "BorderThickness=1",
  "controlStyles[21].styles[2]": "BorderBrush:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\".2\" TintLuminosityOpacity=\".3\" Opacity=\"1\"/>",
  "controlStyles[21].styles[3]": "Background@PointerOver:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\"0\" TintLuminosityOpacity=\".2\" Opacity=\"1\"/>",
  "controlStyles[22].target": "Windows.UI.Xaml.Controls.TextBlock[Text=Back]",
  "controlStyles[22].styles[0]": "Visibility=Collapsed",
  "controlStyles[23].target": "Windows.UI.Xaml.Controls.TextBlock[Text=]",
  "controlStyles[23].styles[0]": "Text=",
  "controlStyles[23].styles[1]": "FontSize=16",
  "controlStyles[24].target": "Button#CloseAllAppsButton > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter@CommonStates",
  "controlStyles[24].styles[0]": "Width=40",
  "controlStyles[24].styles[1]": "Height=40",
  "controlStyles[24].styles[2]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\".3\" TintLuminosityOpacity=\".5\" Opacity=\"1\"/>",
  "controlStyles[24].styles[3]": "BorderBrush:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\".2\" TintLuminosityOpacity=\".3\" Opacity=\"1\"/>",
  "controlStyles[24].styles[4]": "Background@PointerOver:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\"0\" TintLuminosityOpacity=\".2\" Opacity=\"1\"/>",
  "controlStyles[25].target": "Button#CloseAllAppsButton",
  "controlStyles[25].styles[0]": "Margin=0,-102,-33,0",
  "controlStyles[26].target": "Grid#AllAppsRoot",
  "controlStyles[26].styles[0]": "Margin=0,-20,0,-40",
  "controlStyles[27].target": "Border#AcrylicOverlay",
  "controlStyles[27].styles[0]": "Margin=0,0,0,-58",
  "controlStyles[27].styles[1]": "BorderBrush:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\".65\" Opacity=\"1\"/>",
  "controlStyles[27].styles[2]": "BorderThickness=2",
  "controlStyles[27].styles[3]": "Background=Transparent",
  "controlStyles[27].styles[4]": "CornerRadius=8",
  "controlStyles[28].target": "Border#AcrylicBorder",
  "controlStyles[28].styles[0]": "Margin=6,6,6,12",
  "controlStyles[28].styles[1]": "CornerRadius=8",
  "controlStyles[29].target": "Border#DropShadow",
  "controlStyles[29].styles[0]": "Visibility=Collapsed",
  "controlStyles[30].target": "Border#StartDropShadow",
  "controlStyles[30].styles[0]": "Visibility=Collapsed",
  "controlStyles[31].target": "Cortana.UI.Views.TaskbarSearchPage",
  "controlStyles[31].styles[0]": "Margin=5,0,0,8",
  "controlStyles[32].target": "Cortana.UI.Views.TaskbarSearchPage > Grid#RootGrid",
  "controlStyles[32].styles[0]": "BorderBrush:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\".65\" Opacity=\"1\"/>",
  "controlStyles[32].styles[1]": "BorderThickness=2",
  "controlStyles[32].styles[2]": "Padding=3,3,3,-8",
  "controlStyles[32].styles[3]": "CornerRadius=8",
  "controlStyles[33].target": "Border#dropshadow",
  "controlStyles[33].styles[0]": "Visibility=Collapsed",
  "controlStyles[34].target": "Border#LayerBorder",
  "controlStyles[34].styles[0]": "Visibility=Collapsed"
}
```
</details>
