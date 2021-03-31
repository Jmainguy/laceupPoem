# Poem for Lace up Challenge

```
if we make it easy to use
    then users will show up
fi
```

```
try
    to understand their needs
except
    for when they dont know themselves
finally
    come together and build something awesome
```


```
for ease of use in technology
    is something we should all strive for.
```

```
// write maintainable code and 
raise exceptions when things break
```

```
run kubernetes
current state, desired state
it has reconciled
```

```
apiVersion: v1
kind: Person
metadata:
    name: Kross
    creationTimestamp: "1997-10-10T17:16:08Z"
    labels:
        version: 1.2.3  
```

```

func main() {
	slf := identity{}
	go simulation(slf)
}

func simulation(slf identity) {
	go slf.grow()
	go slf.learn()
	go slf.fail()
	go slf.questionReality()
	kiddos := make(chan identity)
	go slf.childProcesses(kiddos)

	select {
	 case newSelf := <-kiddos:
		go simulation(newSelf)
	case <- time.After(time.Nanosecond):
		fmt.Print("Mostly worrying about pointless things")
	case <- time.After(TTL):
		fmt.Printf("Goodybye")
		return
	}
}
```
