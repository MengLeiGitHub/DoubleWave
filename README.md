# DoubleWave
# this is a custom view for android

![GIF](https://github.com/xiaosong520/DoubleWave/blob/master/app/GIF.gif)


## How to Use

###Step one：
>>
```
//module project
        dependencies {
            compile 'com.xiaosong520:doublewaveview:1.0.1'
    }
```


###Step two：
>>
``` 
<com.doublewave.DoubleWaveView
        android:id="@+id/waveView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        DoubleWaveView:speedOne="8"
        DoubleWaveView:speedTwo="6"
        DoubleWaveView:peakValue="20dp"
        DoubleWaveView:waveHeight="200dp"
        DoubleWaveView:waveColor="@color/colorBlue"/>
```

###Step three：
>>
```
 waveView = (DoubleWaveView) findViewById(R.id.waveView);
 waveView.setAnim(false);//if you do not need to set animation effects
 waveView.setAnim(true);//set true to Restart anim
 ```
