## Divider

Demo:

```tsx
import React from 'react';
import { Divider, Row } from '@we-fe/we-ui';

import './demo.less';

export default () => {
  return (
    <div className="Divider-demo-page">
      <Divider>背影</Divider>
      <Row>我与父亲不相见已二年余了，我最不能忘记的是他的背影。</Row>
      <Divider></Divider>
      <Row>
        那年冬天，祖母死了，父亲的差使1也交卸了，正是祸不单行的日子。我从北京到徐州，打算跟着父亲奔丧2回家。到徐州见着父亲，看见满院狼藉3的东西，又想起祖母，不禁簌簌地流下眼泪。父亲说：“事已如此，不必难过，好在天无绝人之路！”
      </Row>
      <Divider>左分割线</Divider>
      <Row>
        回家变卖典质4，父亲还了亏空；又借钱办了丧事。这些日子，家中光景很是惨澹5，一半为了丧事，一半为了父亲赋闲6。丧事完毕，父亲要到南京谋事，我也要回北京念书，我们便同行。
      </Row>
      <Divider orientation="center">中分割线</Divider>
      <Row>
        到南京时，有朋友约去游逛，勾留7了一日；第二日上午便须渡江到浦口，下午上车北去。父亲因为事忙，本已说定不送我，叫旅馆里一个熟识的茶房8陪我同去。他再三嘱咐茶房，甚是仔细。但他终于不放心，怕茶房不妥帖9；颇踌躇10了一会。其实我那年已二十岁，北京已来往过两三次，是没有什么要紧的了。他踌躇了一会，终于决定还是自己送我去。我再三劝他不必去；他只说：“不要紧，他们去不好！”
      </Row>
      <Divider orientation="right">右分割线</Divider>
      <Row>
        我们过了江，进了车站。我买票，他忙着照看行李。行李太多，得向脚夫11行些小费才可过去。他便又忙着和他们讲价钱。我那时真是聪明过分，总觉他说话不大漂亮，非自己插嘴不可，但他终于讲定了价钱；就送我上车。他给我拣定了靠车门的一张椅子；我将他给我做的紫毛大衣铺好座位。他嘱我路上小心，夜里要警醒些，不要受凉。又嘱托茶房好好照应我。我心里暗笑他的迂；他们只认得钱，托他们只是白托！而且我这样大年纪的人，难道还不能料理自己么？我现在想想，我那时真是太聪明了。
      </Row>
      <Divider orientation="left">纵向分割线</Divider>
      <Row>
        <span>首页</span>
        <Divider type="vertical"></Divider>
        <span>详情</span>
        <Divider type="vertical"></Divider>
        <span>帮助</span>
      </Row>
    </div>
  );
};
```

More skills for writing demo: https://d.umijs.org/guide/demo-principle
