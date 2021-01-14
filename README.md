![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21001-single-elicorn-green-840x140-a.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>&nbsp; 


&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21002-row-white-elicorn-green2-840x140-a.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>


&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21003-row-black-elicorn-b2-840x140-a.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>





&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21004-row-black-elicorn-b3-840x140-b.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>



&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21005-row-black-elicorn-b4-840x140-c.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>




&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21006-single-green-elicorn-b1.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>




&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21007-row-elicorn-white-840x140.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>



&nbsp; &nbsp;
...&nbsp;&nbsp; 

&nbsp;&nbsp; 
&nbsp; ![Image of elicorn](https://c0745.paas2.tx.modxcloud.com/assets/images/MIC21008-row-elicorn-white-840x140-b.png)

<p><a href="https://slack.citusdata.com" rel="nofollow"><img src="https://camo.githubusercontent.com/02a19c775bbaf83cfd1f62a8ae110163cd48bda45bce19f64fdb51d54c09ff1a/687474703a2f2f736c61636b2e6369747573646174612e636f6d2f62616467652e737667" alt="Slack Status" data-canonical-src="http://slack.citusdata.com/badge.svg" style="max-width:100%;"></a>
<a href="https://docs.citusdata.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/2c81072c289d1a3fbdb088380d6269c02d4e2493afe02fe64fcff355882aded7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d6c61746573742d627269676874677265656e2e737667" alt="Latest Docs" data-canonical-src="https://img.shields.io/badge/docs-latest-brightgreen.svg" style="max-width:100%;"></a>
<a href="https://circleci.com/gh/citusdata/citus.svg?style=svg" rel="nofollow"><img src="https://camo.githubusercontent.com/da9b83de834ae4f9696234282fcc4725b483e64139acefd364e5e7a5b05e72d2/68747470733a2f2f636972636c6563692e636f6d2f67682f6369747573646174612f63697475732e7376673f7374796c653d737667" alt="Circleci Status" data-canonical-src="https://circleci.com/gh/citusdata/citus.svg?style=svg" style="max-width:100%;"></a>
<a href="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" rel="nofollow"><img src="https://camo.githubusercontent.com/e64f583b3af595dd47f637e3ed32979364f39f5ceecf7a2ebb6fa91a259b1229/68747470733a2f2f636f6465636f762e696f2f67682f6369747573646174612f63697475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Code Coverage" data-canonical-src="https://codecov.io/gh/citusdata/citus/branch/master/graph/badge.svg" style="max-width:100%;"></a></p>

<ul>
<li><a href="#what-is-citus">What is Citus Open Source?</a></li>
<li><a href="#get-started">Get Started</a></li>
<li><a href="#build-apps">Build Apps</a></li>
<li><a href="#whats-being-worked-on">What's being worked on?</a></li>
<li><a href="#architecture">Architecture</a></li>
<li><a href="#need-help">Need Help?</a></li>
<li><a href="#contribute">Contribute</a></li>
<li><a href="#license">License</a></li>
<li><a href="#read-more">Read More</a></li>
</ul>

<h1><a id="user-content-what-is-yugabytedb" class="anchor" aria-hidden="true" href="#what-is-citus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Citus Open Source?</h1>

<p><strong>Citus is an open source extension to Postgres</strong> that distributes your data and your queries across multiple nodes. Because Citus is an extension to Postgres, and not a fork, Citus gives developers and enterprises a scale-out database while keeping the power and familiarity of a relational database. As an extension, Citus supports new PostgreSQL releases, and allows you to benefit from new features while maintaining compatibility with existing PostgreSQL tools.</p>




