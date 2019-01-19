# weeklyCalendar
>weeklyCalendar，周历控件。

纯js，不依赖第三方库<br/>
支持设置默认选中日期<br/>
支持设置禁用日期<br/>

##### js使用示例:
```js
  // 默认周历
  weeklyCalendar('#j_weeklyCalendar',{
     //点击日期回调
    clickDate:function(dateTime){
      console.log(dateTime);
    }
  });  
  
  //设置默认选中日期
    weeklyCalendar('#j_weeklyCalendar2',{
    defaultDate:'2019-01-31',
    //获取选中日期
    getSelectedDate:function(dateTime){  
      console.log("selected",dateTime);
    }
  });  

  //设置禁用日期
    weeklyCalendar('#j_weeklyCalendar3',{
    disabledDate:['2019-01-18','2019-01-19','2019-01-20'],
    clickDate:function(dateTime){
      console.log(dateTime);
    }
  });  
```

##### 效果截图:

![UI](https://upload-images.jianshu.io/upload_images/7598145-492563227f8794d3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/420/format/webp)
