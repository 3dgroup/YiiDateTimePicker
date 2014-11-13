### YiiDateTimePicker
> This Extension based on [DateTimePicker jQuery plugin](http://xdsoft.net/jqplugins/datetimepicker/)

### Install
Create in your extensions folder YiiDateTimePicker folder.

Move downloaded files to YiiDateTimePicker extension folder.

### Usage
Place this code in your view page
```php
    $this->widget('ext.YiiDateTimePicker.jqueryDateTime', array(
        'model' => $model,
        'attribute' => 'date_start',
        'options' => array(), //DateTimePicker options
        'htmlOptions' => array(),
    ));
```

Full DateTimePicker options list you can see at [DateTimePicker Official Page](http://xdsoft.net/jqplugins/datetimepicker/)
