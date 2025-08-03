# Masonry 圖片目錄

這個目錄用於存放瀑布流相冊的圖片。

## 圖片要求

- **格式**：JPG、PNG、WebP
- **尺寸**：建議寬度 300-800px，高度不限
- **檔案大小**：建議小於 500KB

## 如何添加圖片

1. 將你的圖片放入此目錄
2. 在 `_config.redefine.yml` 中更新 `masonry` 配置：

```yaml
masonry:
  - image: /images/masonry/你的圖片.jpg
    title: 圖片標題
    description: 圖片描述
```

## 示例圖片

目前使用以下佔位圖片：
- sample1.jpg - sample12.jpg

你可以替換這些圖片為你自己的照片。 