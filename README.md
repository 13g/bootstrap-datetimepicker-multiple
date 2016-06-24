# bootstrap-datetimepicker-multiple
bootstrap-datetimepicker with support for date multiple.  
在bootstrap-datetimepicker的基础上增加日期多选功能

##USAGE
You can use this function with set the option multiple to true.  
使用本功能只需将multiple选项设为true

	var today = new Date();
    $('.datetimepicker').datetimepicker({
        language: 'zh-CN',
        autoclose: false,
        showMeridian: 'true',
        format: "yyyy-mm-dd",
        startDate: today,
        endDate: new Date(today.getTime()+30*24*3600*1000),
        minView:2,
        multiple:true,
        datesDisabled:[
            new Date(today.getTime()+2*24*3600*1000),
            new Date(today.getTime()+3*24*3600*1000)
        ]
    });

And you can also refer to demo.  
你也可以参照demo。


