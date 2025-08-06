#Design

```python
class Human:

    fruits = {"💗", "🤩", "🕊️", "🙏", "😊", "🎁", "🤝", "🧘", "⛓️"}

    def __init__(self):
        self._piece = input("What is your piece?")
    
    def is_fruit(self):
        return self._piece in Human.fruits

def main():
    me = Human()
    print(me.is_fruit())

if __name__ == "__main__":
    main()

# Galatians 5:22-23
```


# Other Approach

```python
print("💗🤩🕊️🙏😊🎁🤝🧘⛓️".count(input("What is your piece?")) > 0)
```

## Font-Awsome

| 絵文字 | 意味       | Font Awesome代用候補                         | fa-xxx名                          |
| --- | -------- | ---------------------------------------- | -------------------------------- |
| 💗  | Love     | fa-heart                                 | fa-heart                         |
| 🤩  | Joy      | fa-smile-beam                            | fa-smile-beam                    |
| 🕊️ | Peace    | fa-dove (Pro版) / fa-peace                | fa-dove ※Pro / fa-peace (無料版はなし) |
| 🙏  | Patience | fa-praying-hands (Pro版)                  | fa-praying-hands ※Proのみ          |
| 😊  | 親切       | fa-smile                                 | fa-smile                         |
| 🎁  | 善意       | fa-gift                                  | fa-gift                          |
| 🤝  | 誠実       | fa-handshake                             | fa-handshake                     |
| 🧘  | 柔和       | fa-spa / fa-pray / fa-person-running(代用) | fa-spa（リラックスや癒し）                 |
| ⛓️  | 自制       | fa-link / fa-chain                       | fa-link                          |

