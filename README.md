# xamarin-currency-input
Currency input control that formats the currency using the current culture settings. When focus is given, the text is reformatted to simple decimal notation.

The control has the following settings:
- DecimalPlaces -> the number of decimal places to show.
- Amount -> the current amount of money entered

## iOS
For iOS the UITextField is subclassed.

## Android

For Android the EditText class is subclassed.

## reactive UI

With this control you can simply bind your currency observable:

this.Bind(this.ViewModel, x => x.Bedrag, x => x.txf_bedrag1.Amount);
