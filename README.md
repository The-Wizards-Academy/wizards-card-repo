# The Wizards Card

This repository acts as your "Wizards Card" for The Wizards Academy. By forking it, you identify yourself as an initiate.

## How to Set Your Password

To gain entry to the Academy, you must set a password.

1.  **Fork this Repository:** Click the "Fork" button in the top-right corner.
2.  **Generate Your Hash:**
    *   Think of a secret password.
    *   Go to a trusted online SHA-256 generator (like [this one](https://xorbin.com/tools/sha256-hash-calculator)).
    *   Type your password and generate the hash. Copy the long hash string.
3.  **Create Your Card:**
    *   In *your forked* repository, create a new file named `wizard-card.json`.
    *   Paste the following code into the file, replacing `"PASTE_YOUR_HASH_HERE"` with the hash you just generated:

    ```json
    {
      "hash": "PASTE_YOUR_HASH_HERE"
    }
    ```
4.  **Commit the File:** Save and commit the `wizard-card.json` file to your fork.

You are now ready to enter the Academy.
