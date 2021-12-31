- 👋 Hi, I’m @SOGDM
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SOGDM/SOGDM is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
struct Book
{
	char name[20];
	short price;

};
int main()
{
	struct Book b1 = {"C语言程序设计",55};
struct Book* pb = &b1;
printf("%s\n", pb->name);
printf("%d元\n", pb->price);
}
