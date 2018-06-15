### Code Blocks

####  The Basics

@fa[arrow-circle-down]

+++
@title[Sample block]

```go
// NewUser creates a new ACME user.
func NewUser(msg []byte) (*User, error) {
  vu := &User{}
  if err := json.Unmarshal(msg, vu); err != nil {
    return vu, err
  }

  return vu, nil
}

```

###### Code-blocks let you present any <p> **static code** with auto-syntax highlighting

---

### Code block
##### Using
#### **Code Presenting**

@fa[arrow-circle-down]

+++

```go
package acme

import "encoding/json"

// User represents a ACME user.
type User struct {
  CostCenter     string `json:"cost_center" csv:"cost_center"`
  CustomID       string `json:"employee_id" csv:"employee_id"`
  Department     string `json:"department" csv:"department"`
  Email          string `json:"email" csv:"email"`
  FirstName      string `json:"first_name" csv:"first_name"`
  HireDate       string `json:"hire_date" csv:"hire_date"`
  JobTitle       string `json:"job_title" csv:"job_title"`
  LastName       string `json:"last_name" csv:"last_name"`
  Location       string `json:"location" csv:"location"`
  ManagerID      string `json:"manager_id" csv:"manager_id"`
  EmployeeStatus string `json:"employeeStatus" csv:"employeeStatus"`
}

// NewUser creates a new ACME user.
func NewUser(msg []byte) (*User, error) {
  vu := &User{}
  if err := json.Unmarshal(msg, vu); err != nil {
    return vu, err
  }

  return vu, nil
}

```

@[1-3]
@[5-18]
@[20-28]

###### Use code-presenting to **step-through** code <p> from directly within the presentation
