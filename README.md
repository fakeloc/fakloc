# fakeloc

Synthetic address fixtures for form validation, interface demos, and import/export tests.

[Generate US address test data](https://fakeloc.tech/us-tax-free-address-generator)

![fakeloc US five-state address generator interface](./product.png)

## Reproduce the input that broke a form

Random inputs help explore a form. Repeatable inputs help investigate a failure. Keep the seed, settings, and data version together when saving a fixture.

- Generate synthetic addresses with reference-paired city, state, and ZIP fields.
- Use the Alaska, Delaware, Montana, New Hampshire, and Oregon preset.
- Generate batches of 1–1,000 records.
- Export CSV, JSON, or TXT for test workflows.

## Check a round trip

1. Generate a fixture with a fixed seed.
2. Fill the address form and export its stored values.
3. Import the output into the next system.
4. Compare the original and resulting ZIP codes as text, including leading zeros.

Street addresses and profiles are synthetic. They are test fixtures, not verified delivery destinations or proof of residence. The five-state preset does not guarantee tax exemption.

[Open the US address fixture generator](https://fakeloc.tech/us-tax-free-address-generator)
