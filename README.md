# LitJsonUPM

It's a unity package wrapper for Litjson.

Litjson的Unity Package 封装，方便在项目中引用

# Import

in `Packages/manifest.json`, add:

    "com.ms.litjson":"http://192.168.2.240/zilch/unity/LitJson.git"

# Attention

If use IL2Cpp, you must make whole LitJson Preserved in link.xml, cause there are some reflection code in LitJSON.

由于LitJson中存在反射代码，在使用IL2Cpp的时候，务必将整个LitJson保留，不要被Strip