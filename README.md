This golang package is a generic helper to create client payload.

The structure of a pagination
```golang
// Pageable describes a generic model
type Pageable struct {
	Limit  int         `json:"limit"`
	Offset int         `json:"offset"`
	Total  int64       `json:"total"`
	Data   interface{} `json:"data"`
}
```
