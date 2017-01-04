# SHOP

| 字段 | 描述 | 约束 |
:-----|:-----|:----|
id| 商户ID | 整数
name| 商户名称 | 100个字符以内
image_url| 商户头图 |
cat_id| 分类ID | 如：外卖、KTV
cat_name| 分类名 |
type_id| 子分类ID | 外卖的分类从0-4，全部为99
type_name| 子分类名 |
tel| 商户电话 | 
boss_tel| 商户老板电话 |
open_time| 营业时间 |
lat| 纬度 | 范围：-90至90
lng| 经度 | 范围：-180至180
addr| 商户地址 |
is_vip| 是否VIP商户 | 1为vip，0为非vip
intro| 老板一句话描述（商户简介） | 
menu_image_urls| 菜单图们 | 一张或多张图
distance| 距离 | 距离当前位置的距离,当当前位置获取不到时，客户端请传递的坐标均设置为0，则距离返回空字符串。
comments_count | 评论数 | 被评论数
score| 商户评星 | 用户评星的平均值
partner | 平台合作商户 | 即vip商户
err_num | 商户纠错错误码 | 1=电话有误，2=地址错了，3=商户已不存在
created_at | 创建时间 | 