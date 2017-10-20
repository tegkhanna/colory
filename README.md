# Colory
> Fetches color name using hex value.


## Usage example


```python

>>> from colors import Color
>>> a=Color('#ffffff')
>>> a.nearest_match()
'Exact Match Found: white'
>>> b=Color('#000000')
>>> b.nearest_match()
'Nearest Match: black'

Mix colors
>>> a.mix(b)
>>> a.nearest_match()
'Nearest Match: medium grey'

```



## Meta

Apoorva Pandey – apoorvapandey365@gmail.com

Distributed under the BSD license.

[https://github.com/apoorvaeternity](https://github.com/apoorvaeternity)

## Contributing

1. Fork it (<https://github.com/apoorvaeternity/colory/>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -m 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

