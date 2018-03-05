# Lecture 3: Congruences

Even integers are those that can be written as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f1738bbe3646e5962be59daa0aa34d56.svg?invert_in_darkmode" align=middle width=17.29464pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>. The
odd integers are those that can be written as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6b00e9fecad2c902c76321d82303b8ce.svg?invert_in_darkmode" align=middle width=45.60501pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

We can split the integers into three classes; those that are <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/bcb0fe7fc0db81671c2169cae7d31ceb.svg?invert_in_darkmode" align=middle width=17.29464pt height=22.831379999999992pt/> for some
integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>, those that are <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/263b06bca66c6813dfa9f6a44b37410c.svg?invert_in_darkmode" align=middle width=45.60501pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>, and those that are
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/734b57c261dea2f08d2d8716eae9801c.svg?invert_in_darkmode" align=middle width=45.60501pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

These classes also have particular properties. For example, the some of an
integer in the second class and an integer in the third class will always be in
the first class.

We don't have to stop with 3. We could divide integers into 4 different classes
according to their remainders when divided by 4, and so on.

## 3.1 Congruences

Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> be a positive integer and let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> be integers.

Basically <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode" align=middle width=37.66158pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) means that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> have the same remainder
when you divide them by <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>.

**Definition** We say <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode" align=middle width=37.66158pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) if <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/60ea14f79e208ac729da92907e80ab04.svg?invert_in_darkmode" align=middle width=35.835195000000006pt height=22.831379999999992pt/>.

**Equivalent definition** We say <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode" align=middle width=37.66158pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) if <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7e1cb77fdc8d07448d4c6e039adff15d.svg?invert_in_darkmode" align=middle width=76.69513500000001pt height=22.831379999999992pt/> for some
integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

Note we are talking about "congruence modulo _n_" as a relation here, which is
not quite the same as using a mod operation.

### Questions

Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/28ee715d5d1a7e3258d779bc39c1ac4e.svg?invert_in_darkmode" align=middle width=46.575374999999994pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>)? Yes (because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/> divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/41915154d7ae04faaf1d0554254afb09.svg?invert_in_darkmode" align=middle width=44.748825pt height=21.18732pt/>)

Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/46ad6646f0f2bc4c5cb7107e5ec6f831.svg?invert_in_darkmode" align=middle width=46.575374999999994pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>)? No (because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/> doesn't divide <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f6cd67074967c6d3a14bff23a79b9308.svg?invert_in_darkmode" align=middle width=44.748825pt height=21.18732pt/>)

What integers are congruent to 3 modulo 4?

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/42ae412532c2efe6d2b426935ae4a87b.svg?invert_in_darkmode" align=middle width=188.12804999999997pt height=13.789957499999998pt/></p>

Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/32ca4fc1bca482eb9ef4f9e7bd618227.svg?invert_in_darkmode" align=middle width=38.356065pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>)? Yes

Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1e34abd80752d8cc4d2a2087772734c8.svg?invert_in_darkmode" align=middle width=46.575374999999994pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/005c128d6e551735fa5d938e44e7a613.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>)? No (because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/005c128d6e551735fa5d938e44e7a613.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/> doesn't divide <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f42092c7722c08040b568b4c8c4633c4.svg?invert_in_darkmode" align=middle width=44.748825pt height=21.18732pt/>)

Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9cc8590fb356ea9c45445b22de8a6dfe.svg?invert_in_darkmode" align=middle width=85.45647pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>)? Yes (because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/> does divide <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8f2aa1ca93f54b25a4fb531c3169d9c8.svg?invert_in_darkmode" align=middle width=151.47231pt height=21.18732pt/>)

## 3.2 Working with congruences

When working with congruences modulo some fixed integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>, we can "substitute
in" just like we can with equalities.

```
If a ≡ b (mod n) and b ≡ c (mod n), then a ≡ c (mod n).
```

We can add, subtract and multiply congruences just like we can with equations.

```
If a1 ≡ b1 (mod n) and a2 ≡ b2 (mod n), then
* a1 + a2 ≡ b1 + b2 (mod n)
* a1 - a2 ≡ b1 - b2 (mod n)
* a1a2 ≡ b1b2 (mod n)
```

### Examples

Suppose we know that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/da81de6df84636e6e01fb8d000dcfd47.svg?invert_in_darkmode" align=middle width=39.53185500000001pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/b01b41af6f5831f6288bf2e8d02b4c90.svg?invert_in_darkmode" align=middle width=38.786055000000005pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>).

Adding these, we see <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/b5e2bc7ca0091cb912d78008f9760fff.svg?invert_in_darkmode" align=middle width=68.272215pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>).

So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a9fdf874cea88f992d3e75b3459a8f42.svg?invert_in_darkmode" align=middle width=68.272215pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>) (because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9e662f0811221d30d3f9a16e8750ea36.svg?invert_in_darkmode" align=middle width=38.356065pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecf4fe2774fd9244b4fd56f7e76dc882.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>)).

Suppose we know that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/28511b3bbfcb44d12b384283b07287aa.svg?invert_in_darkmode" align=middle width=47.751165pt height=21.18732pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9612eecfec9dadf1a81d296bd2473777.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8646b8ea90ee667fc0a87ed126ca55df.svg?invert_in_darkmode" align=middle width=47.751165pt height=21.18732pt/> (mod 5).

Subtracting the second from the first, we see <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a37a211c8051207d8953bb30d63658f7.svg?invert_in_darkmode" align=middle width=52.317375000000006pt height=21.18732pt/> (mod 5)

So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9de4a8bb431a97ce3b1080e42d15aa50.svg?invert_in_darkmode" align=middle width=39.53185500000001pt height=21.18732pt/> (mod 5) (because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4312d202054149de87b9fae9067df28a.svg?invert_in_darkmode" align=middle width=51.141585pt height=21.18732pt/> (mod 5))

### Question 3.2 (one part)

**Fact.** If <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dcd3ae550ce96263451646616e90da7.svg?invert_in_darkmode" align=middle width=51.588570000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/01b80cc4168770b9d6da224491b80865.svg?invert_in_darkmode" align=middle width=51.588570000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>),
then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ae3587dfd8f4b93dc71e67e169a0a2cc.svg?invert_in_darkmode" align=middle width=122.26384499999999pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

**Proof.**

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3143eb2ca274d39be64a70bcacdf53f1.svg?invert_in_darkmode" align=middle width=51.588570000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/365c7d2a2144c8c6dc443c7b3b4e1447.svg?invert_in_darkmode" align=middle width=49.762185pt height=22.831379999999992pt/>

This means that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c5124e4950f8c13b2a1266930509ef5a.svg?invert_in_darkmode" align=middle width=98.30089499999998pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aa90653a26bc63b138fb304972d81589.svg?invert_in_darkmode" align=middle width=15.110535000000004pt height=22.831379999999992pt/>.

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6de5bb4dfd32a40c0a5378dc6d3304c1.svg?invert_in_darkmode" align=middle width=51.588570000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8f137f09c643ac49b938636d3a1820b5.svg?invert_in_darkmode" align=middle width=49.762185pt height=22.831379999999992pt/>

This means that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fde986ee68d19ecf84a054601b57945d.svg?invert_in_darkmode" align=middle width=98.30089499999998pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a8ebf8c468236800b8ed78d42ddbfa57.svg?invert_in_darkmode" align=middle width=15.110535000000004pt height=22.831379999999992pt/>.

So, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6caddce95f285d6a5cab030f2e2ff508.svg?invert_in_darkmode" align=middle width=240.43750499999996pt height=24.65759999999998pt/>.

So, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/dec7eac7b97b72c4b1a132f235b12671.svg?invert_in_darkmode" align=middle width=243.35635499999998pt height=24.65759999999998pt/>.

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8d4321bc66d31b165e50d12f574686b9.svg?invert_in_darkmode" align=middle width=51.133995000000006pt height=22.831379999999992pt/> is an integer, this means <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/359c30d0c7fdf72faee984faf8344fea.svg?invert_in_darkmode" align=middle width=146.8302pt height=24.65759999999998pt/>.

So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ae3587dfd8f4b93dc71e67e169a0a2cc.svg?invert_in_darkmode" align=middle width=122.26384499999999pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

### Substituting in

In the two most common situations, "substituting in" using congruences is legal:

**Fact:**

If <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/173d22d9962e402a59c6b597cf67eae3.svg?invert_in_darkmode" align=middle width=64.86661500000001pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a06dc6cdb6e4b1f42520d444a27bc707.svg?invert_in_darkmode" align=middle width=37.587495000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e40b8381c7135bbc679c944f476c7054.svg?invert_in_darkmode" align=middle width=66.30888pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

**Proof:**

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a06dc6cdb6e4b1f42520d444a27bc707.svg?invert_in_darkmode" align=middle width=37.587495000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/27479478212b40e89e45654b014e4510.svg?invert_in_darkmode" align=middle width=36.027255000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), we have <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/eff9b54c7f7d4ed709316a6d7d35a979.svg?invert_in_darkmode" align=middle width=69.961815pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

So because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/173d22d9962e402a59c6b597cf67eae3.svg?invert_in_darkmode" align=middle width=64.86661500000001pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), we have <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/b271b69defa147888a2d6bc86ddd1b0b.svg?invert_in_darkmode" align=middle width=66.30888pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

**Fact:**

If <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/88ac20d87287039893b3242416a13bfe.svg?invert_in_darkmode" align=middle width=44.77539pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a06dc6cdb6e4b1f42520d444a27bc707.svg?invert_in_darkmode" align=middle width=37.587495000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0123386305a1cc9dda9540a40431f913.svg?invert_in_darkmode" align=middle width=46.217655pt height=22.831379999999992pt/>
(mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

**Proof:**

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a06dc6cdb6e4b1f42520d444a27bc707.svg?invert_in_darkmode" align=middle width=37.587495000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/27479478212b40e89e45654b014e4510.svg?invert_in_darkmode" align=middle width=36.027255000000004pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), we have <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f0ed183ae50eb714ec790d2db016325d.svg?invert_in_darkmode" align=middle width=51.69697500000001pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

So because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/88ac20d87287039893b3242416a13bfe.svg?invert_in_darkmode" align=middle width=44.77539pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>), we have <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0123386305a1cc9dda9540a40431f913.svg?invert_in_darkmode" align=middle width=46.217655pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>).

But you can't substitute into exponents, logarithm bases, etc:

**Example:**

We know <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2877c8f5f14a7a21e883f15d4bd29647.svg?invert_in_darkmode" align=middle width=38.356065pt height=21.18732pt/> (mod 5), but <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/883b34dcf6a2f713bcfd9cb094cdb899.svg?invert_in_darkmode" align=middle width=52.283055pt height=26.76201000000001pt/> (mod 5).

In some situations we can also "divide through" a congurence by an integer.

If a ≡ b (mod n) and d divides a, b and n, then

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/913355c4ae33404ed1d7bdc8a0811e68.svg?invert_in_darkmode" align=middle width=103.18489499999998pt height=33.812129999999996pt/></p>