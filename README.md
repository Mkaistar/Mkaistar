
Given url "https%3A%2F%2Fstarxmodofficial.000webhostapp.com%2Flogin.php"
    And header Content-Type = 'application/x-www-form-urlencoded'
    And form field username = "check"
    And form field password = "Password"
    And request {}
    And header Content-Type = 'application/json'
    When method POST
    Then status 200
