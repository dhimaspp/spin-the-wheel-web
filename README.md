# spin_the_wheel

### Compiling the App for Web (JavaScript)
1. **Ensure Web Support is Enabled**:
    Verify that web support is enabled in your Flutter installation:
    ```bash
    flutter config --enable-web
    ```

2. **Compile to Web**:
    Build the app for web using the following command:
    ```bash
    flutter build web
    ```

3. **Deploy the Web App**:
    The compiled web app will be available in the `build/web` directory. You can serve it locally using a simple server:
    ```bash
    cd build/web
    python3 -m http.server
    ```
    Open a web browser and navigate to http://localhost:8000/index.html to interact with the web version of the app.
    Or you can deploy the contents of `build/web` to any web hosting service.
