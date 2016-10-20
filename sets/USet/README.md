# Implementations of the USet interface

type USet interface {
	Len() int
	Add(x interface{}) bool
	Delete(x interface{})
	Find(x interface{}) (interface{}, bool)
}

** see ../interfaces.go **

## integer

Un-ordered set of integers (i.e golang map type)