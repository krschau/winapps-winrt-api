---
-api-id: T:Microsoft.UI.Xaml.Input.HoldingEventHandler
-api-type: winrt delegate
---

<!-- Delegate syntax.
public delegate void HoldingEventHandler(System.Object sender, Microsoft.UI.Xaml.Input.HoldingRoutedEventArgs e)
-->

# Microsoft.UI.Xaml.Input.HoldingEventHandler

## -description
Represents the method that will handle the [Holding](../microsoft.ui.xaml/uielement_holding.md) event.

## -parameters

### -param sender

The object where the event handler is attached.

### -param e

Event data for the event.

## -remarks

## -examples

The following code example shows scenario 3 from the [Input sample](https://github.com/microsoftarchive/msdn-code-gallery-microsoft/tree/411c271e537727d737a53fa2cbe99eaecac00cc0/Official%20Windows%20Platform%20Sample/Input%20XAML%20user%20input%20events%20sample). This code shows some usage patterns for direct manipulation using the [Holding](../microsoft.ui.xaml/uielement_holding.md), [Tapped](../microsoft.ui.xaml/uielement_tapped.md), [DoubleTapped](../microsoft.ui.xaml/uielement_doubletapped.md), and [RightTapped](../microsoft.ui.xaml/uielement_righttapped.md) events.

[!code-xaml[Scenario3Xaml](../microsoft.ui.xaml/code/input/csharp/Scenario3.xaml#SnippetScenario3Xaml)]

[!code-csharp[Scenario3Code](../microsoft.ui.xaml/code/input/csharp/Scenario3.xaml.cs#SnippetScenario3Code)]

[!code-vb[Scenario3Code](../microsoft.ui.xaml/code/input/vbnet/Scenario3.xaml.vb#SnippetScenario3Code)]

## -see-also
