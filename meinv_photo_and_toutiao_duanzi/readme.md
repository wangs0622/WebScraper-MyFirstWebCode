# <font color = red>introduction</font>

In this python file, I write two main-functions. One is `"main_meinv()"` and another is `"main_toutiao"`.

The first mian-function is used to download the image of beautiful girls, which website's domain is [www.mm131.com](www.mm131.com). if you want to download the image that you like. You need to change the `url` and `range()`, which is under the `url`, in the `main_meinv` function.

For example:

You want to download those photo in [http://www.mm131.com/qingchun/2194.html](http://www.mm131.com/qingchun/2194.html). You need to change `url` and `range` as the following:

	url = "http://img1.mm131.com/pic/2194/1.jpg"
	for i in range(1,50)

The second main-function is used to download the jokes in [https://www.toutiao.com/](https://www.toutiao.com/). The jokes will be downloaded in a "result.txt" file, which is in the current folder.

At the bottle on this python file, you can see:

	if __name__ == "__main__":
		main_toutiao()

when you run this program it will call `main_toutiao()` function. if you want to download photo, you should change as the followinf:

	if __name__ == "__main__":
		main_meinv()