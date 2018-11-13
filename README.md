# Protect your site with Static Mirroring

As part of our [ongoing efforts](https://contentdistribution.page.link/pye) to protect publishers from large scale attacks, we want to share a simple technique that can not only minimize your attack surface but also protect your site from network-level attacks.

[Static mirroring](https://contentdistribution.page.link/effstatic) helps protect your site by using hosting-as-a-service platforms shared by many different sites. By using a shared domain name, encryption, and scalable infrastructure, these services help protect you against attacks such as keyword filtering and DDoS. With proper [security settings](https://contentdistribution.page.link/securityplanner), they are also easier to harden against attacks that replace content than your own servers.

You can generate a static mirror of your existing site easily through one of [the many free static generators](https://contentdistribution.page.link/staticgen) for different web frameworks. Wordpress in particular offers effective plugins for generating a static version of your Wordpress site that require no technical expertise. [Simply Static](https://contentdistribution.page.link/simplystatic) and [WP2Static](https://contentdistribution.page.link/wp2static) are two well regarded options.

In order to help secure your site and reduce filtering, you can follow this three-step process requiring very little technical expertise:



1.  Generate a static copy of your site using a [free generator](https://contentdistribution.page.link/staticgen), including the above plugins for WordPress.
1.  Host that static copy on one or more public Cloud providers:
    *   [Amazon S3](https://contentdistribution.page.link/amazonhost)
    *   [Google Cloud Storage](https://contentdistribution.page.link/cloudhost)
    *   [Microsoft Azure Storage](https://contentdistribution.page.link/azurehost)
    *   [Alibaba Cloud Storage](https://contentdistribution.page.link/alibabahost)
1.  Distribute your static mirror's HTTPS link to your users.

You will now have a copy of your site that you can update as frequently as you want and that is harder to attack. A network can still block your domain name, but the HTTPS URL of any of your static mirrors will be very difficult for them to block. Once you're set up, check out [Keeping Your Site Alive](https://contentdistribution.page.link/eff) at the EFF for more ways to protect your site.
