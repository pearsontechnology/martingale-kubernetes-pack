# Martinglae Kubernetes Pack

**Name:** Kubernetes

This pack provides screens that allow users to view and manage a Kubernetes cluster.

**Required Endpoints:**

/api[/:env]/kube should point to Kubernetes Master (EG: https://mykube)

Where :env is an optional value to route to different clusters.


## Configuration Options

### env: Environment name for the instance of the plugin.


### host: Hostname or host path to the instance of the Kubernetes API.
**Default Value:** /api/kubernetes

### headers: Any custom headers such as authorization that need to be sent through.


## Included Pages
### KubeDashboard: Side Nav

<svg fill="currentColor" preserveAspectRatio="xMidYMid meet" height="64" width="64" viewBox="0 0 800 1500" style="vertical-align: middle;">
  <g>
    <path
 d="m 332.4224,306.75103 c -12.3524,10e-4 -22.36803,10.66908 -22.36656,23.82828 2e-5,0.20196 0.0431,0.39495 0.0477,0.59571 -0.0182,1.78801 -0.10828,3.94209 -0.0477,5.49883 0.29458,7.58986 2.0201,13.39882 3.05868,20.39152 1.88151,14.96661 3.45809,27.37301 2.48517,38.90428 -0.94618,4.34833 -4.28655,8.3251 -7.26435,11.08932 l -0.52571,9.07308 c -13.42272,1.06629 -26.93523,3.01884 -40.43185,5.95707 -58.07599,12.64319 -108.07839,41.32643 -146.1473,80.0539 -2.47022,-1.61582 -6.79183,-4.58843 -8.07689,-5.49883 -3.99336,0.51706 -8.02934,1.69846 -13.286117,-1.23724 -10.009375,-6.46023 -19.125693,-15.37758 -30.15662,-26.11948 -5.054429,-5.13839 -8.714653,-10.03136 -14.719871,-14.98433 -1.363741,-1.1248 -3.444955,-2.64611 -4.970346,-3.80336 -4.694882,-3.58901 -10.232338,-5.46074 -15.580124,-5.63631 -6.875733,-0.22573 -13.494781,2.35182 -17.826338,7.5609 -7.7005348,9.2606 -5.235105,23.41486 5.496056,31.61832 0.108888,0.0831 0.224843,0.14777 0.334542,0.22911 1.474618,1.14614 3.280368,2.61471 4.635804,3.57425 6.37255,4.51132 12.193712,6.82068 18.543215,10.40196 13.377113,7.92098 24.466904,14.48887 33.263086,22.40777 3.434922,3.5107 4.035279,9.69689 4.492429,12.37238 l 7.168768,6.14037 C 52.171771,594.54355 34.410904,662.94289 44.90699,732.63594 l -9.367191,2.61195 c -2.468809,3.05678 -5.957395,7.86662 -9.606226,9.3022 -11.508462,3.47557 -24.460588,4.75186 -40.097313,6.32366 -7.341293,0.5853 -13.675609,0.23601 -21.458517,1.64965 -1.71298,0.31114 -4.099725,0.90734 -5.973974,1.32889 -0.06515,0.0132 -0.126017,0.0317 -0.191167,0.0457 -0.10216,0.0227 -0.236374,0.0702 -0.334542,0.0916 -13.183102,3.05411 -21.65196,14.67236 -18.92555,26.11947 2.727054,11.4498 15.604043,18.4127 28.866242,15.67169 0.09574,-0.021 0.234753,-0.0245 0.334543,-0.0457 0.149722,-0.0328 0.281535,-0.1025 0.430126,-0.1374 1.848739,-0.38911 4.165566,-0.82204 5.78281,-1.23724 7.651794,-1.96437 13.193501,-4.85065 20.0725517,-7.3776 14.7993054,-5.08939 27.0566223,-9.34102 38.9981013,-10.99768 4.987444,-0.37453 10.24214,2.95055 12.855992,4.35325 l 9.749525,-1.60383 c 22.435654,66.69403 69.453569,120.60052 128.990039,154.42567 l -4.0623,9.34803 c 1.46422,3.62985 3.07919,8.54108 1.98848,12.12577 -4.3413,10.79414 -11.77738,22.1874 -20.24494,34.88928 -4.09993,5.86825 -8.29594,10.42229 -11.99574,17.138 -0.88533,1.607 -2.01288,4.0755 -2.86751,5.7738 -5.74853,11.793 -1.53184,25.3756 9.51057,30.4727 11.11178,5.1292 24.90445,-0.2806 30.87349,-12.0974 0.009,-0.017 0.0393,-0.029 0.0477,-0.046 0.006,-0.013 -0.006,-0.033 0,-0.046 0.8502,-1.6754 2.05471,-3.8776 2.77192,-5.4531 3.16899,-6.9608 4.22344,-12.926 6.4519,-19.6583 5.91795,-14.25314 9.1694,-29.20835 17.31604,-38.52716 2.23081,-2.5518 5.86778,-3.53319 9.63853,-4.50119 l 5.06593,-8.79814 c 51.90301,19.10193 110.00012,24.22782 168.03593,11.59338 13.23943,-2.88223 26.02082,-6.61246 38.37681,-11.08932 1.42378,2.42144 4.06976,7.0762 4.77918,8.24826 3.83189,1.19534 8.0144,1.81262 11.42223,6.64442 6.09501,9.9844 10.26323,21.79616 15.34117,36.06315 2.22882,6.7322 3.33031,12.6977 6.49968,19.6584 0.72237,1.5865 1.92085,3.8196 2.77193,5.4988 5.95649,11.8552 19.79286,17.2834 30.92129,12.1433 11.04105,-5.0999 15.26238,-18.6813 9.51056,-30.4728 -0.85473,-1.6982 -2.02989,-4.1668 -2.9153,-5.7737 -3.70017,-6.71556 -7.89551,-11.22419 -11.99574,-17.09222 -8.46826,-12.70146 -15.49169,-23.25304 -19.83359,-34.04696 -1.81549,-5.56713 0.3063,-9.02944 1.7205,-12.64733 -0.84691,-0.9308 -2.65922,-6.18815 -3.72776,-8.66066 61.87302,-35.02856 107.51022,-90.94533 128.94226,-155.52545 2.89411,0.43613 7.92432,1.28946 9.55835,1.60383 3.36384,-2.12724 6.45677,-4.90279 12.52145,-4.44489 11.94156,1.65606 24.19852,5.90902 38.99811,10.99767 6.87918,2.52662 12.42066,5.45944 20.07255,7.42343 1.61726,0.41511 3.93403,0.80239 5.7828,1.19142 0.14866,0.0349 0.28033,0.1047 0.43013,0.13739 0.0999,0.0214 0.23881,0.0248 0.33454,0.0458 13.26297,2.73761 26.14225,-4.22122 28.86624,-15.67169 2.72336,-11.44779 -5.74159,-23.06874 -18.92554,-26.11948 -1.91769,-0.4181 -4.63734,-1.12818 -6.49969,-1.46635 -7.78298,-1.41325 -14.11719,-1.06472 -21.45851,-1.64965 -15.6368,-1.57103 -28.58867,-2.84868 -40.09732,-6.32367 -4.6924,-1.74537 -8.03059,-7.09898 -9.65401,-9.3022 l -9.03265,-2.5203 c 4.68323,-32.48627 3.42044,-66.29594 -4.6836,-100.12465 -8.17949,-34.14369 -22.63476,-65.37141 -41.9134,-92.88453 2.31702,-2.01959 6.69267,-5.73478 7.93344,-6.82772 0.3627,-3.84797 0.0511,-7.88244 4.20568,-12.14326 8.79574,-7.91934 19.88641,-14.48611 33.26308,-22.40777 6.34931,-3.5816 12.2187,-5.89032 18.59101,-10.40196 1.44102,-1.02023 3.40874,-2.63591 4.92255,-3.80336 10.72889,-8.20622 13.19907,-22.35962 5.49606,-31.61832 -7.70301,-9.25869 -22.62979,-10.13081 -33.35867,-1.92459 -1.52713,1.15967 -3.59934,2.67246 -4.97035,3.80336 -6.00494,4.9533 -9.71351,9.84569 -14.76766,14.98433 -11.03033,10.74246 -20.1476,19.70457 -30.15662,26.1653 -4.33722,2.42105 -10.69001,1.58335 -13.57294,1.42054 l -8.50694,5.8196 C 494.245,453.5082 428.19926,422.32629 357.08295,416.26901 c -0.19891,-2.85752 -0.45949,-8.02269 -0.52571,-9.57714 -2.91142,-2.67119 -6.42845,-4.95168 -7.31215,-10.72273 -0.97292,-11.53127 0.65145,-23.93767 2.53297,-38.90428 1.03857,-6.9927 2.76409,-12.80166 3.05867,-20.39152 0.067,-1.72536 -0.0405,-4.22898 -0.0477,-6.09454 -0.001,-13.1592 -10.01417,-23.82948 -22.36656,-23.82828 z m -28.00599,166.3398 -6.64306,112.49705 -0.47792,0.22911 c -0.44555,10.06412 -9.0842,18.10034 -19.69021,18.10034 -4.34456,0 -8.35468,-1.33774 -11.61341,-3.62006 l -0.19116,0.0916 -96.20488,-65.39033 c 29.56767,-27.87713 67.38705,-48.47832 110.97254,-57.96691 7.96171,-1.73328 15.91988,-3.01938 23.8481,-3.94084 z m 56.05977,0 c 50.88636,6.00081 97.94643,28.09367 134.00818,61.95357 l -95.58358,64.97792 -0.33454,-0.13739 c -8.48392,5.94122 -20.43719,4.46709 -27.05015,-3.4826 -2.70895,-3.25672 -4.13032,-7.08601 -4.30127,-10.95185 l -0.0956,-0.0457 z m -225.76841,103.92803 87.84131,75.33406 -0.0956,0.45824 c 7.92865,6.60882 9.09785,18.07715 2.48518,26.02783 -2.70877,3.25685 -6.33464,5.44127 -10.22745,6.46113 l -0.0956,0.36659 -112.59746,31.16008 c -5.730855,-50.24496 6.61981,-99.08705 32.68959,-139.80793 z m 394.80798,0.0457 c 13.05151,20.28346 22.93478,42.93805 28.81845,67.49822 5.8131,24.26568 7.27198,48.48797 4.87476,71.89729 L 450.038,685.2084 l -0.0956,-0.45824 c -10.13415,-2.65563 -16.36227,-12.53972 -14.00299,-22.45358 0.96659,-4.06125 3.215,-7.49695 6.26072,-10.03538 l -0.0477,-0.22912 87.36339,-74.96747 z m -215.11085,81.10784 35.98721,0 22.36656,26.80683 -8.02902,33.45126 -32.30725,14.89268 -32.40283,-14.9385 -8.02902,-33.45126 z m 115.36938,91.73893 c 1.52929,-0.0741 3.05191,0.0581 4.54022,0.32077 l 0.19117,-0.22912 116.46859,18.87934 c -17.04523,45.91617 -49.66188,85.69414 -93.24178,112.31375 l -45.21104,-104.70702 0.1433,-0.1833 c -4.15308,-9.25269 0.003,-20.1031 9.55836,-24.51565 2.4464,-1.12969 5.00229,-1.75524 7.5511,-1.87877 z m -195.6118,0.45824 c 8.88811,0.11951 16.86036,6.03442 18.92555,14.70939 0.96683,4.06119 0.49627,8.08512 -1.09921,11.6392 l 0.33454,0.41242 -44.73311,103.65307 C 165.76721,855.0512 132.45502,816.52205 114.63521,769.24903 l 115.46497,-18.78769 0.19117,0.22912 c 1.29154,-0.22789 2.6014,-0.33785 3.87113,-0.32077 z m 97.54304,45.4113 c 3.09607,-0.1091 6.23764,0.5 9.22382,1.87877 3.91435,1.80733 6.93819,4.65303 8.84148,8.06496 l 0.43013,0 56.92002,98.61248 c -7.38714,2.37437 -14.98153,4.40359 -22.74889,6.09454 -43.53187,9.47692 -86.92542,6.60546 -126.21812,-6.23201 l 56.77665,-98.42918 0.0956,0 c 3.40686,-6.10651 9.868,-9.74962 16.67933,-9.98956 z"
 />

  </g>
</svg>

**Dynamic Path:** config.env?&#x60;/kubernetes/${config.env}&#x60;:&#x27;/kubernetes&#x27;

**Path:** /kube

**Path:** /kubernetes/:env


### Namespaces: Side Nav

**Icon:** Cluster

**Dynamic Path:** config.env?&#x60;/kubernetes/${config.env}/namespaces&#x60;:&#x27;/kubernetes/namespaces&#x27;

**Path:** /kubernetes/namespaces

**Path:** /kubernetes/:env/namespaces


### Pod: 

**Path:** /kubernetes/namespace/:name/pod/:id

**Path:** /kubernetes/:env/namespace/:name/pod/:id


### Logs: 

Provides a view of the current logs for a given resource

**Path:** /kubernetes/namespace/:name/pod/:id/:container/logs

**Path:** /kubernetes/:env/namespace/:name/pod/:id/:container/logs


### Ingresses: 

**Path:** /kubernetes/namespace/:name/ingresses

**Path:** /kubernetes/:env/namespace/:name/ingresses


### Pods: 

**Path:** /kubernetes/namespace/:name/pods

**Path:** /kubernetes/:env/namespace/:name/pods


### Secrets: 

**Path:** /kubernetes/namespace/:namespace/secrets

**Path:** /kubernetes/:env/namespace/:namespace/secrets


### Secret: 

**Path:** /kubernetes/namespace/:namespace/secret/:name

**Path:** /kubernetes/:env/namespace/:namespace/secret/:name


### ThirdPartyResources: Side Nav

**Icon:** Gateway

**Dynamic Path:** config.env?&#x60;/kubernetes/${config.env}/thirdpartyresources&#x60;:&#x27;/kubernetes/thirdpartyresources&#x27;

**Path:** /kubernetes/thirdpartyresources

**Path:** /kubernetes/:env/thirdpartyresources


### Ingress: 

**Path:** /kubernetes/namespace/:namespace/ingress/:name

**Path:** /kubernetes/:env/namespace/:namespace/ingress/:name


### ThirdPartyResource: 

**Path:** /kubernetes/thirdpartyresource/:name

**Path:** /kubernetes/:env/thirdpartyresource/:name


### Daemonset: 

**Path:** /kubernetes/namespace/:namespace/daemonset/:name

**Path:** /kubernetes/:env/namespace/:namespace/daemonset/:name


### Replicasets: 

**Path:** /kubernetes/namespace/:namespace/replicasets

**Path:** /kubernetes/:env/namespace/:namespace/replicasets


### Replicaset: 

**Path:** /kubernetes/namespace/:namespace/replicaset/:name

**Path:** /kubernetes/:env/namespace/:namespace/replicaset/:name


### Daemonsets: 

**Path:** /kubernetes/namespace/:namespace/daemonsets

**Path:** /kubernetes/:env/namespace/:namespace/daemonsets


### Quotas: 

**Path:** /kubernetes/namespace/:namespace/resourcequotas

**Path:** /kubernetes/:env/namespace/:namespace/resourcequotas


### Quota: 

**Path:** /kubernetes/namespace/:namespace/resourcequotas/:name

**Path:** /kubernetes/:env/namespace/:namespace/resourcequotas/:name


### Deployments: 

**Path:** /kubernetes/namespace/:namespace/deployments

**Path:** /kubernetes/:env/namespace/:namespace/deployments


### Services: 

**Path:** /kubernetes/namespace/:namespace/services

**Path:** /kubernetes/:env/namespace/:namespace/services


### Deployment: 

**Path:** /kubernetes/namespace/:namespace/deployment/:name

**Path:** /kubernetes/:env/namespace/:namespace/deployment/:name


### Service: 

**Path:** /kubernetes/namespace/:namespace/service/:name

**Path:** /kubernetes/:env/namespace/:namespace/service/:name



