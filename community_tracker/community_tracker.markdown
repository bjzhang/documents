智能社区动态推送
====

难用的rss reader
----

之前用rss reader的问题是不方便记笔记，没法跟据我的关注程度自动调整推送内容。

凑合用的kindle + evernote
----

后来改用kindle和evernote，可以用kindle做笔记或收藏邮件/文章到evernote。kindle的笔记可以通过clipping.io转换到evernote。这样解决了笔记问题。但是这东西还是没法影响推送内容。

只能自己定制了？
----

想支持反馈需要把关注点和gmail结合。
如果是关注邮件可以通过gapi设置gmail中指定标签实现。
如果是笔记，可以用gapi搜索邮件或mailling list achieve。

kindle send to xxx解密：kindle其实没法发文章出去，我看到的做法是把文章链接或evernote token做为参数给服务器（例如狗耳朵这和rss 2 kindle服务器），服务器下载文章后，再发送到evernote.

