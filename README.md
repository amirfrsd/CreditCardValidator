# Shetab Credit Card Validator on Swift
Shetab Credit Card Validator and type detector on Swift.

Inspired from [https://github.com/MaxKramer/ObjectiveLuhn]()

# Usage
## Validating

```Swift
let number = "6219861030762784"
   
let v = CreditCardValidator()
   
if v.validate(string: number) {
  // Card number is valid
} else {
  // Card number is invalid
}

```

## Detect Card Type

```Swift
let number = "6219 8610 3076 2784"
   
let v = CreditCardValidator()
if let type = v.typeFromString(number) {
	println(type.name) // Saman, Pasargad, Mellat and etc.
} else {
	// I Can't detect type of credit card
}

```
# Contribution
Contributions are very welcomed 👍😃.
