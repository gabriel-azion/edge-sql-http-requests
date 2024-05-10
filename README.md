# Edge SQL http requests

## Running HTTP Requests with REST Client Extension

This guide will help you run HTTP requests using the REST Client extension in Visual Studio Code.

### Prerequisites

1. [Visual Studio Code](https://code.visualstudio.com/download) installed on your machine.
2. [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) extension installed in Visual Studio Code.

### Steps to Run HTTP Requests

1. Open Visual Studio Code.

2. Navigate to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window. It looks like four squares.

3. In the Extensions view, search for "REST Client". Click on the first result and then click on the Install button.

4. Once the REST Client extension is installed, open the [edge-sql.http](file:///Users/gabriel.franca/edge-sql-testing/edge-sql.http#1%2C1-1%2C1) file in Visual Studio Code.

5. You will see a series of HTTP requests in this file. Each request is separated by `###`.

6. To run a request, click on the "Send Request" link that appears above the request.

   For example, to run the following request:

   ```http
   GET https://api.azion.com/v4/edge_sql/databases HTTP/1.1
   ```

   Click on the "Send Request" link above it.

7. The response will appear in a separate pane to the right.

Remember to replace placeholders like `{id_database}` and `[TOKEN VALUE]` with actual values before sending the requests.

That's it! You can now run HTTP requests directly from Visual Studio Code using the REST Client extension.