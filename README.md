# 服务计算作业6——cloudgo-data
课程地址为：http://blog.csdn.net/pmlpml/article/details/78602290



-------------------
使用xorm来改写提供的代码。</br>

按照教程先下载好docker和mysql并运行mysql：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129195459184?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
</br>
建立好数据库：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129195546339?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
</br>运行并监听8080端口：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129230040028?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

</br>插入数据：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129230119386?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
</br>查询数据：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129230138608?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

</br>测试xorm的性能：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129231206678?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
</br>测试sql的性能：</br>
![这里写图片描述](http://img.blog.csdn.net/20171129231134031?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzY4MTY5MTI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
</br>对比结果：</br>
虽然xorm形式上比较简洁，但是性能并没有sql好，可以从上面的性能对比测试中看出。
