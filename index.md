---
layout: report
student: Boxuan Li 
organisation: coala
organisation_link : https://coala.io
project: Meta-review
project_link: https://summerofcode.withgoogle.com/projects/#5188493739819008
tarball: 
mentors: >
 [Hemang Kumar](https://github.com/hemangsk/) & [Surya Widi](https://github.com/blazeu) & [Andrew Dassonville](https://github.com/andrewda)
phase:
 - Bonding : https://gitlab.com/coala/GSoC/GSoC-2018/milestones/14
 - Phase 1 : https://gitlab.com/coala/GSoC/GSoC-2018/milestones/15
 - Phase 2 : https://gitlab.com/coala/GSoC/GSoC-2018/milestones/16
 - Phase 3 : https://gitlab.com/coala/GSoC/GSoC-2018/milestones/17
bio: >
 I'm a final year student (expected graduation date: May 2019) of Computer Science at The University of Hong Kong. I participated in GSoC and worked with [coala](http://coala.io) to implement a meta-review system, which collects and tracks GitHub reactions used by coala community to generate meaningful analysis. I also improved usability of [gh-board](http://github.com/coala/gh-board), a serverless kanban board, fixing some issues and extending it to track reviews & meta-reviews.
social:
 - GitHub:
   - username: li-boxuan
   - link: https://github.com/li-boxuan
 - GitLab:
   - username: li-boxuan
   - link: https://gitlab.com/li-boxuan
 - Gitter:
   - username: li-boxuan
   - link: https://gitter.im/li-boxuan
 - LinkedIn:
   - username: Li Boxuan 
   - link: https://www.linkedin.com/in/li-boxuan-427510104
email: liboxuanhk@gmail.com
blog: http://li-boxuan.github.io/
activity:
 - 0:
   - repo: community
   - link: https://github.com/coala/community/commit/2929576df9c20144aad9db8a5e326c1853375158
   - details: > 
      Set up meta_review app
 - 1:
   - repo: community
   - link: https://github.com/coala/community/commit/aae015127c96b85a1cd9188199a6e4a46693d9f7
   - details: >
      Change meta-review models

 - 2:
   - repo: community
   - link: https://github.com/coala/community/commit/78e1e3a542a1654982f55cde4e08bbf97ec81c3c
   - details: >
      Implement meta-review scoring & ranking system

 - 3:
   - repo: gh-board
   - link: https://github.com/coala/gh-board/commit/e452f41ddda6abe149442d5240675b3ae3333e6a
   - details: >
      nav.jsx: Fix broken link on header

---

### Meta-review


#### Work Done

coala [community](https://github.com/coala/community) website now has a meta-review
[ranking list](http://coala-community.netlify.com/meta-review/). coala
gh-board [website](https://coala-gh-board.netlify.com/)
now has a column displaying review comments that need to be meta-reviewed. I also
fixed many issues around [gh-board](https://github.com/coala/gh-board) repo.
Apart from all above, I do some other contributions to the community, including
doing reviews, and fixing several issues around coala & coala-bears repo.

#### Challenges

Most things went smoothly. The biggest challenge for me was that I did not have serious
frontend experience. Before I applied for this project, I had no frontend development
knowledge at all, while two thirds of my project was about javascript and React.
Luckily, org admin and all my mentors were very willing to help and review my work.
coala community always do extremely careful reviews and expect high quality of code.
It was hard work for me, but I did learn a lot at the same time.

#### Work to be done

The ranking list on community website is very basic. It could be prettified and improved.
As it is a ranking list, filtering, sorting & searching options could be added.
The algorithm between that meta-review ranking system is basic: it uses naive iterative
algorithm to calculate scores, which can be enhanced in the future.

There are still many issues around with gh-board. A major improvement which can be done
is GitLab support - it currently only supports GitHub.

