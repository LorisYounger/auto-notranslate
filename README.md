# Auto-notranslate
Auto disable or enable `notranslate` class to allow Translator such as GoogleTranslator to allow webpage translation

## Logic
Remove all `notranslate` classes
Add `notranslate` for the class containing 'code'
 * For example: `amber-display-codeblock` `amber-code`

## Advantages
 * Support dynamic loading, and new content will also be judged
 * Loading only processes elements whose class names have actually changed, avoiding performance waste

# 自动化允许翻译
自动禁用或启用 `notranslate` 类以允许网页翻译器（如谷歌翻译）允许网页翻译

## 逻辑
去除所有 `notranslate` 类
为包含 'code' 类 添加 `notranslate`
 * 例如: `amber-display-codeblock` `amber-code`

## 优点
 * 支持动态加载, 新增内容也会进行判断
 * 加载只处理那些类名实际发生变化的元素, 避免性能浪费
