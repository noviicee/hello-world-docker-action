# Hello World Docker Action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

* `who-to-greet` <br>
**Required** <br>
The name of the person to greet. <br>
*Default*: `"World"`.

## Outputs

* `time` <br>
The time we greeted you.

## Example usage

```yml
uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Noviicee'
```
<hr>

> Make sure to make the `entrypoint.sh` file executable by running the following command on your system.
