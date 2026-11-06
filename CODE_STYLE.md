# Scientific Notebook Style Guide

## General Principles

- Prefer clarity over verbosity.
- Use concise, neutral, technical wording.
- Keep the existing language unless asked otherwise.
- Avoid unnecessary stylistic changes.
- Do not rewrite working code for aesthetics alone.

## Print Statements

- Remove decorative emojis.
- Avoid exaggerated success messages.
- Prefer short descriptions of completed operations.
- Preserve all printed variables, values, and formatting
  needed for debugging or interpreting experiments.
- Do not change messages consumed programmatically.

## Comments

- Explain why a step exists when useful.
- Remove purely decorative or redundant comments.
- Preserve important methodological explanations.
- Avoid motivational phrases and unnecessary narration.
- Do not introduce claims unsupported by the code.

## Formatting

- Preserve existing code structure and indentation.
- Do not reorder imports or statements.
- Do not automatically format entire cells.
- Do not split, merge, add, or remove notebook cells.

## Examples

Before:
print("✅ Dekomposisi Selesai!")

After:
print("Dekomposisi selesai.")

Before: # 🚀 Sekarang kita mulai training model!!!

After: # Training model GRU

Before: # Menghitung RMSE
rmse = np.sqrt(mean_squared_error(y_true, y_pred))

After:
rmse = np.sqrt(mean_squared_error(y_true, y_pred))

## Review Standard

Every cosmetic change must have a clear reason.
If an edit is unnecessary or potentially behavioral,
preserve the original.
