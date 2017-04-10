[![Build Status](https://travis-ci.org/GlobalFreightSolutions/gfs-delivery-address.svg?branch=master)](https://travis-ci.org/GlobalFreightSolutions/gfs-delivery-address)


# &lt;gfs-delivery-address&gt;

The `gfs-delivery-address` widget provides the users address, the selected service and the droppoint address if a droppoint is selected.

## Install

```bash
# via bower
$ bower install --save gfs-delivery-address
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/gfs-delivery-address/gfs-delivery-address.html">
```

3. Start using it!

<!---
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="gfs-delivery-address.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<gfs-delivery-address
    default-street-address="100 Station Road, Horsham, RH13 5UZ, United Kingdom">
</gfs-delivery-address>
```

More info, demo and all the available properties can be found at [GFS widget portal](http://developer.justshoutgfs.com/info/documentation/gfs-checkout/the-gfs-checkout-widgets/delivery-address-widget/ "The GFS Delivery Address Widget")


## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)
