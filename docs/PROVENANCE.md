# Generative AI Use and Provenance

This file documents generative AI use that influenced artifacts in this
project.

## Entry 1
-   **Student:** Jay Patel
-   **Artifact:** `starter/exercise1.py`
-   **Provenance label:** AI-ASSISTED
-   **AI tool:** ChatGPT
-   **Purpose:** Get guidance on implementing the menu-loading/filtering
    requirements and understand the expected structure of the Exercise 1
    solution.
-   **Influence:** ChatGPT provided implementation guidance and
    explanations. The final code was reviewed and adapted by me to match the assignment requirements.
-   **Validation:** Ran the program and checked that the available menu
    items under the required price limit were printed in ascending price
    order. The output was also checked against the provided `menu.json`
    data.
-   **PR or commit:** Exercise 1 implementation commit.

## Entry 2

-   **Student:** Jay Patel
-   **Artifact:** `starter/exercise2.py`
-   **Provenance label:** AI-ASSISTED
-   **AI tool:** ChatGPT
-   **Purpose:** Get guidance on implementing the `Cart` class,
    including adding items, increasing the quantity of an existing item,
    removing items, clearing the cart, calculating the total, and
    implementing `__repr__`.
-   **Influence:** ChatGPT explained implementation approaches and
    helped identify the difference between the menu's `id` field and the
    cart's required `item_id` field. I implemented and adapted
    the final solution.
-   **Validation:** Tested adding multiple items and adding the same
    item more than once, checked that quantities increased instead of
    creating duplicate lines, verified item removal and clearing, and
    checked that the total was rounded to two decimal places.
-   **PR or commit:** `9f6e755` --- Add cart class.

## Entry 3

-   **Student:** Jay Patel
-   **Artifact:** `starter/exercise3.py`
-   **Provenance label:** AI-ASSISTED
-   **AI tool:** ChatGPT
-   **Purpose:** Get guidance on implementing the required cart business
    rules and exception handling for invalid quantities, unavailable
    items, and removing items that are not in the cart.
-   **Influence:** ChatGPT provided explanations and implementation
    guidance for the required exceptions and validation logic. Then I implemented and adapted the final solution.
-   **Validation:** Tested the required error cases using `try/except`,
    including `ValueError` for invalid quantities, `OutOfStockError` for
    unavailable items, and `KeyError` when removing an item that is not
    in the cart. The resulting behavior was checked against the
    assignment requirements.
-   **PR or commit:** `e18efb8` --- Enforce cart business rules.

## Entry 4

-   **Student:** Jay Patel
-   **Artifact:** `starter/tests/test_cart.py`
-   **Provenance label:** AI-ASSISTED
-   **AI tool:** ChatGPT
-   **Purpose:** Get guidance on the additional tests required for
    Exercise 5, including multiple-item totals, adding the same item
    twice, invalid quantity, and unavailable items.
-   **Influence:** ChatGPT helped identify and explain appropriate test
    cases and how they should verify the required behavior, then I adapted the final tests.
-   **Validation:** Ran `pytest -v` and verified that all tests passed
    (`7 passed`).
-   **PR or commit:** `51f8213` --- Add cart tests.

## Notes

AI was used as a software-engineering assistance tool for explanations,
implementation guidance, debugging, and test guidance. I reviewed, adapted, ran, and tested the resulting work and is responsible
for the final submitted project.
