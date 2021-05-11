# Language Engineering Challenge

- **Timebox:** 3 hours
- **Technologies:** Whatever you're interviewing for
- **Tests:** Nice to have
- **Documentation:** Nice to have

Pick one of these challenges to get started. Good luck! ✨

## Challenge #1: Configuration file validator

Consider a made-up configuration format called ANON. ANON is very similar to JSON, with a few changes.

Example:

```
{
	"heroes": [
		{
			"real_name": "Clint Barton",
			"superhero_name": "Hawkeye",
		},
		{
			// Dr Strange does not have a separate superhero name
			"real_name": "Dr. Strange",
			"superhero_name": "Dr. Strange",
			"famous_dialogues": """Kaecilius: Mister...
Dr. Strange: Doctor
Kaecilius: Mister Doctor?
Dr. Strange: It's Strange.
Kaecilius: Maybe. Who am I to judge?"""
		},
	],
}
```

ANON supports trailing commas, allows comments (using `//`), and supports multi-line strings, in addition to everything else that JSON supports.

Write a validator for ANON. Here are some of the rules that the validator can check for:

1. Opened brackets must be closed.
2. Opened strings must be closed.
3. Escape sequences must be valid. (`"\"` is not a valid string, `"\\"` is. Similarly, `"\""` is valid too).
4. Triple quotes cannot be used in keys. For example: `{"""key""": "value"}` is invalid, `{"key": """value"""}` is valid.

Add as many rules as you can think of. For simplicity, assume that single quotes will not be used anywhere except inside strings.

### What does ANON stand for?
It can be ANy Other Notation. Or _ANON's Not an Object Notation_. Or _Another Notorious Object Notation_. You can even come up with your own expansion of the acronym.
