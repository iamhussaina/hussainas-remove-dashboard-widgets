# Hussainas - Remove Dashboard Widgets Snippet

A simple, standalone WordPress code snippet (procedural) to remove default dashboard widgets for a cleaner admin interface.

This snippet removes the following widgets:
* Welcome Panel
* At a Glance
* Activity (including Recent Comments and Recently Published)
* Quick Draft
* WordPress Events and News
* Site Health Status

## 🚀 Installation & Usage

This is not a plugin. It's a snippet designed to be included in your (child) theme.

1.  **Download:** Download the `hussainas-remove-dashboard-widgets.php` file from this repository.
2.  **Place File:** Place the file inside your active theme's folder. For better organization, you might create an `includes` folder (e.g., `wp-content/themes/your-theme/includes/`).
3.  **Include File:** Open your theme's `functions.php` file and add the following line of code at the end:

    ```php
    // Load the dashboard widget removal snippet
    require_once get_template_directory() . '/includes/hussainas-remove-dashboard-widgets.php';
    ```
    *Note: Adjust the path (`/includes/...`) based on where you placed the file in step 2.*

4.  **Done:** Save the `functions.php` file. The dashboard widgets will now be removed.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome. Please open an issue or submit a pull request for any improvements or bug fixes.
