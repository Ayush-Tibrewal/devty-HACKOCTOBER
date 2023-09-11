# Adding Custom Module to Devty

Following are the steps on how to add a new module to Devty:

- Create a new folder inside `src/modules`.

**Devty follows `CamelCase` convention for naming modules folders**

- Inside the new folder, make sure to create a vue file with the name same as the folder name.

- Now add this module details to the `src/stores/routes.ts` file.

**All icons from [`Google's MaterialIcon`](https://fonts.google.com/icons) are available when using the `icon` property**

**If you want to add a custom image as icon for the module, use the `image` property**

- Now update the vue file you created earlier and add the required functionality and you'er done!

🎉 Yay, you've just create a new module inside Devty!

[< Prev](UNDERSTANDING_FILE_STRUCTURE.md) [Back to home](README.md)
