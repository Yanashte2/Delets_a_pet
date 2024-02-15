pm.test("error message", function () {
    var jsonData = pm.response.json();
    pm.expect(jsonData.message).to.eql("Pet not found");
});
