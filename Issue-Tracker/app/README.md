Project Issue Tracker

Write the following tests in tests/2_functional-tests.js:

Create an issue with every field: POST request to /api/issues/{project}<br>
Create an issue with only required fields: POST request to /api/issues/{project}<br>
Create an issue with missing required fields: POST request to /api/issues/{project}<br>
View issues on a project: GET request to /api/issues/{project}<br>
View issues on a project with one filter: GET request to /api/issues/{project}<br>
View issues on a project with multiple filters: GET request to /api/issues/{project}<br>
Update one field on an issue: PUT request to /api/issues/{project}<br>
Update multiple fields on an issue: PUT request to /api/issues/{project}<br>
Update an issue with missing _id: PUT request to /api/issues/{project}<br>
Update an issue with no fields to update: PUT request to /api/issues/{project}<br>
Update an issue with an invalid _id: PUT request to /api/issues/{project}<br>
Delete an issue: DELETE request to /api/issues/{project}<br>
Delete an issue with an invalid _id: DELETE request to /api/issues/{project}<br>
Delete an issue with missing _id: DELETE request to /api/issues/{project}<br>
