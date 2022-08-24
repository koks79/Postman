# Postman
Requests via the postman
Add somthing to check the changes in this file
pm.test("The 1st pet in the list is the latest added with the name '" + jsonData.pets[0].name + "'", function () {
    pm.expect(jsonData.pets[0].name).to.eql(pm.collectionVariables.get("name"));
});pm.test("The 1st pet in the list is the latest added with the name '" + jsonData.pets[0].name + "'", function () {
    pm.expect(jsonData.pets[0].name).to.eql(pm.collectionVariables.get("name"));
});