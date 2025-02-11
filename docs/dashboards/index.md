---
slug: /dashboards
title: Dashboards (Classic)
---

import useBaseUrl from '@docusaurus/useBaseUrl';

<img src={useBaseUrl('img/icons/dashboards.png')} alt="icon" width="75"/>

Dashboards are a powerful forensic tool to create searches and view search results based on data available through a search.

:::sumo
You're viewing our legacy dashboard solution. [Dashboards (New)](/docs/dashboards-new) allows you to analyze metric and log data on the same dashboard, in a streamlined user experience.
:::

<Iframe url="https://www.youtube.com/embed/FWzqVitfAfo"
        width="854px"
        height="480px"
        id="myId"
        className="video-container"
        display="initial"
        position="relative"
        allow="accelerometer; autoplay=1; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
        />

import Iframe from 'react-iframe';

import DocCardList from '@theme/DocCardList';
import {useCurrentSidebarCategory} from '@docusaurus/theme-common';

See the following options to view and modify settings for dashboards:

<DocCardList items={useCurrentSidebarCategory().items}/>
