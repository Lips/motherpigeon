All about the motherpigeonbrooklyn.com site, and various motherpigeon assets:

Site code is hosted here:
https://github.com/Lips/motherpigeon

I used github because it's free, fast, reliable, and doesn't usually need to be changed frequently.
So even editing in the browser is usually just fine. For more complicated changes,

a local copy can be cloned for faster change/review times without getting mixed up in cache updates.
It's all based on Foundation 5.2.3, as seen in this commit:
https://github.com/Lips/motherpigeon/commit/2167e388a011d0a98cce646687ef852c89d472e5

Using github pages depend on two things:
- Branch titled gh-pages
- A CNAME file with the domain:
https://github.com/Lips/motherpigeon/blob/gh-pages/CNAME
- A CNAME (Or "A record?" I always get these confused) record with the registrar, pointing to github.

Mailing list: Mailchimp
Site email: alias as provided by yahoo

Todo:
- Should maybe update to Foundation 6?
  https://get.foundation/templates.html

- Upload images to github instead of relying on 3rd party image hosting.
Maybe make a new branch for them and link directly to file so as to not
get a bunch of binary data into the main branch history.
Or just put them in google drive or whatever.
