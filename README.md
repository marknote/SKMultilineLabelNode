# SKMultilineLabelNode
SKLabelNode that really supports multiple lines of text

## Features
- Specify a width, height will be automatically caculated.
- Support not only English, but also other languages like Chines, Japanese, which does not separate words using space; 

## Sample

```swift
	let messageLabel = SKMultilineLabelNode(text: "不能部署在此处", labelWidth: 	Int(boxSize * 1.5), pos: messagePosition)
	messageLabel.fontColor = UIColor.whiteColor()
	messageLabel.fontSize = 18.0		
	
```
will display as below:

![screen](sample.jpg)
