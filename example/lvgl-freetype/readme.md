# 【lvgl-freetype】使用说明
## 1、menuconfig配置
### 1.1、LV_USE_FREETYPE
- 使用Freetype需要在menuconfig打开LV_USE_FREETYPE选项
![](./img/lv_use_freetype.png)

### 1.2、分区表配置
- 字库文件比较大，默认分区表分配空间不足，需使用自定义分区表
![](./img/csv.png)

## 2、IDF版本
- 使用 5.1 版本
