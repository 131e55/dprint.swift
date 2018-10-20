
# dprint.swift

### Swift 3+

### Example

```swift
// ViewController.swift
class ViewController: UIViewController {

    override func viewDidLoad() {

        super.viewDidLoad()

        dprint("Hello", 12345, Date())
    }
}
```

⬇ Output if only DEBUG flag exists ⬇

`<ViewController.swift:viewDidLoad():7> Hello 12345 2017-09-01 20:25:52 +0000`
