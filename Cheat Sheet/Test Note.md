## jdsd
```sh
export SHELL=fish
```


HEre's what it looks like

```ts
type Maybe<T> = T | null;

export const shout(word: string): Maybe<string> => {
	if (word != '') {
		return word.toUpper();
	}
	return null;
};
```