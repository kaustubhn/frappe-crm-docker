# This is a easy to use docker compose for Frappe CRM


Convert the below JSON into a base64 encoded string
```
[
  {
    "url": "https://github.com/frappe/erpnext",
    "branch": "v15.39.3"
  },
  {
    "url": "https://github.com/frappe/hrms",
    "branch": "v15.33.0"
  },
  {
    "url": "https://github.com/frappe/crm",
    "branch": "v1.24.7"
  }
]
```
APPS_JSON_BASE64=WwogIHsKICAgICJ1cmwiOiAiaHR0cHM6Ly9naXRodWIuY29tL2ZyYXBwZS9lcnBuZXh0IiwKICAgICJicmFuY2giOiAidjE1LjM5LjMiCiAgfSwKICB7CiAgICAidXJsIjogImh0dHBzOi8vZ2l0aHViLmNvbS9mcmFwcGUvaHJtcyIsCiAgICAiYnJhbmNoIjogInYxNS4zMy4wIgogIH0sCiAgewogICAgInVybCI6ICJodHRwczovL2dpdGh1Yi5jb20vZnJhcHBlL2NybSIsCiAgICAiYnJhbmNoIjogInYxLjI0LjciCiAgfQpd
and Set the variable in docker compose APPS_JSON_BASE64 to the value
