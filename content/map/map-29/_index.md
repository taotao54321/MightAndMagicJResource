+++
title = "バーン地上D3"
+++

<!-- SVG {{{ -->
<svg width="593" height="593" viewbox="0 0 593 593">
<defs>
<symbol id="svg-asset-cell-bg-light" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="32" stroke="none" fill="#808080" />
</symbol>
<symbol id="svg-asset-cell-bg-dark" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="32" stroke="none" fill="#6060A0" />
</symbol>
<symbol id="svg-asset-boundary-wall-open" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#FFFFFF" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#FFFFFF" />
</symbol>
<symbol id="svg-asset-boundary-wall-closed" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="3" stroke="none" fill="#FFFFFF" />
</symbol>
<symbol id="svg-asset-boundary-door-open" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#FFFFFF" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#FFFFFF" />
<rect x="10" y="0" width="12" height="3" stroke="none" fill="#FFA000" />
</symbol>
<symbol id="svg-asset-boundary-door-closed" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#FFFFFF" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#FFFFFF" />
<rect x="10" y="0" width="12" height="3" stroke="none" fill="#FF0000" />
</symbol>
<symbol id="svg-asset-boundary-forest-open" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#00FF00" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#00FF00" />
</symbol>
<symbol id="svg-asset-boundary-forest-closed" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="3" stroke="none" fill="#00FF00" />
</symbol>
<symbol id="svg-asset-boundary-mountain-open" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#FF8000" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#FF8000" />
</symbol>
<symbol id="svg-asset-boundary-mountain-closed" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="3" stroke="none" fill="#FF8000" />
</symbol>
<symbol id="svg-asset-boundary-sea-open" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#00FFFF" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#00FFFF" />
</symbol>
<symbol id="svg-asset-boundary-sea-closed" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="3" stroke="none" fill="#00FFFF" />
</symbol>
<symbol id="svg-asset-boundary-desert-open" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="10" height="3" stroke="none" fill="#FFFF00" />
<rect x="22" y="0" width="10" height="3" stroke="none" fill="#FFFF00" />
</symbol>
<symbol id="svg-asset-boundary-desert-closed" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="3" stroke="none" fill="#FFFF00" />
</symbol>
<symbol id="svg-asset-boundary-wall-open-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-open" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-open-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-open" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-open-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-open" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-open-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-open" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-closed-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-closed" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-closed-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-closed" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-closed-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-closed" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-wall-closed-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-wall-closed" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-open-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-open" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-open-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-open" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-open-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-open" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-open-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-open" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-closed-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-closed" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-closed-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-closed" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-closed-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-closed" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-door-closed-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-door-closed" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-open-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-open" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-open-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-open" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-open-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-open" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-open-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-open" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-closed-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-closed" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-closed-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-closed" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-closed-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-closed" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-forest-closed-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-forest-closed" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-open-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-open" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-open-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-open" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-open-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-open" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-open-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-open" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-closed-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-closed" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-closed-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-closed" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-closed-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-closed" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-mountain-closed-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-mountain-closed" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-open-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-open" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-open-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-open" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-open-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-open" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-open-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-open" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-closed-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-closed" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-closed-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-closed" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-closed-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-closed" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-sea-closed-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-sea-closed" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-open-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-open" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-open-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-open" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-open-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-open" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-open-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-open" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-closed-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-closed" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-closed-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-closed" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-closed-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-closed" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-boundary-desert-closed-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-boundary-desert-closed" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<symbol id="svg-asset-barrier" width="32" height="32" viewbox="0 0 32 32">
<rect x="0" y="0" width="32" height="3" stroke="none" fill="#A0E0E0" />
</symbol>
<symbol id="svg-asset-barrier-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-barrier" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-barrier-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-barrier" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-barrier-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-barrier" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-barrier-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-barrier" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<image id="svg-asset-num-00" href="/MightAndMagicJResource/asset/map/num-00.png" width="16" height="16" />
<image id="svg-asset-num-01" href="/MightAndMagicJResource/asset/map/num-01.png" width="16" height="16" />
<image id="svg-asset-num-02" href="/MightAndMagicJResource/asset/map/num-02.png" width="16" height="16" />
<image id="svg-asset-num-03" href="/MightAndMagicJResource/asset/map/num-03.png" width="16" height="16" />
<image id="svg-asset-num-04" href="/MightAndMagicJResource/asset/map/num-04.png" width="16" height="16" />
<image id="svg-asset-num-05" href="/MightAndMagicJResource/asset/map/num-05.png" width="16" height="16" />
<image id="svg-asset-num-06" href="/MightAndMagicJResource/asset/map/num-06.png" width="16" height="16" />
<image id="svg-asset-num-07" href="/MightAndMagicJResource/asset/map/num-07.png" width="16" height="16" />
<image id="svg-asset-num-08" href="/MightAndMagicJResource/asset/map/num-08.png" width="16" height="16" />
<image id="svg-asset-num-09" href="/MightAndMagicJResource/asset/map/num-09.png" width="16" height="16" />
<image id="svg-asset-num-10" href="/MightAndMagicJResource/asset/map/num-10.png" width="16" height="16" />
<image id="svg-asset-num-11" href="/MightAndMagicJResource/asset/map/num-11.png" width="16" height="16" />
<image id="svg-asset-num-12" href="/MightAndMagicJResource/asset/map/num-12.png" width="16" height="16" />
<image id="svg-asset-num-13" href="/MightAndMagicJResource/asset/map/num-13.png" width="16" height="16" />
<image id="svg-asset-num-14" href="/MightAndMagicJResource/asset/map/num-14.png" width="16" height="16" />
<image id="svg-asset-num-15" href="/MightAndMagicJResource/asset/map/num-15.png" width="16" height="16" />
<image id="svg-asset-icon-castle" href="/MightAndMagicJResource/asset/map/icon-castle.png" width="16" height="16" />
<image id="svg-asset-icon-church" href="/MightAndMagicJResource/asset/map/icon-church.png" width="16" height="16" />
<image id="svg-asset-icon-desert" href="/MightAndMagicJResource/asset/map/icon-desert.png" width="16" height="16" />
<image id="svg-asset-icon-downstairs" href="/MightAndMagicJResource/asset/map/icon-downstairs.png" width="16" height="16" />
<image id="svg-asset-icon-dummy" href="/MightAndMagicJResource/asset/map/icon-dummy.png" width="16" height="16" />
<image id="svg-asset-icon-encounter" href="/MightAndMagicJResource/asset/map/icon-encounter.png" width="16" height="16" />
<image id="svg-asset-icon-event" href="/MightAndMagicJResource/asset/map/icon-event.png" width="16" height="16" />
<image id="svg-asset-icon-food-shop" href="/MightAndMagicJResource/asset/map/icon-food-shop.png" width="16" height="16" />
<image id="svg-asset-icon-forest" href="/MightAndMagicJResource/asset/map/icon-forest.png" width="16" height="16" />
<image id="svg-asset-icon-guild" href="/MightAndMagicJResource/asset/map/icon-guild.png" width="16" height="16" />
<image id="svg-asset-icon-inn" href="/MightAndMagicJResource/asset/map/icon-inn.png" width="16" height="16" />
<image id="svg-asset-icon-item-shop" href="/MightAndMagicJResource/asset/map/icon-item-shop.png" width="16" height="16" />
<image id="svg-asset-icon-lava" href="/MightAndMagicJResource/asset/map/icon-lava.png" width="16" height="16" />
<image id="svg-asset-icon-pub" href="/MightAndMagicJResource/asset/map/icon-pub.png" width="16" height="16" />
<image id="svg-asset-icon-sea" href="/MightAndMagicJResource/asset/map/icon-sea.png" width="16" height="16" />
<image id="svg-asset-icon-swamp" href="/MightAndMagicJResource/asset/map/icon-swamp.png" width="16" height="16" />
<image id="svg-asset-icon-town" href="/MightAndMagicJResource/asset/map/icon-town.png" width="16" height="16" />
<image id="svg-asset-icon-training" href="/MightAndMagicJResource/asset/map/icon-training.png" width="16" height="16" />
<image id="svg-asset-icon-upstairs" href="/MightAndMagicJResource/asset/map/icon-upstairs.png" width="16" height="16" />
<image id="event-dir" href="/MightAndMagicJResource/asset/map/event-dir.png" width="32" height="32" />
<symbol id="svg-asset-event-dir-north" width="32" height="32" viewbox="0 0 32 32">
<use href="#event-dir" x="0" y="0" transform="translate(0 0) rotate(0)"></use>
</symbol>
<symbol id="svg-asset-event-dir-east" width="32" height="32" viewbox="0 0 32 32">
<use href="#event-dir" x="0" y="0" transform="translate(32 0) rotate(90)"></use>
</symbol>
<symbol id="svg-asset-event-dir-south" width="32" height="32" viewbox="0 0 32 32">
<use href="#event-dir" x="0" y="0" transform="translate(32 32) rotate(180)"></use>
</symbol>
<symbol id="svg-asset-event-dir-west" width="32" height="32" viewbox="0 0 32 32">
<use href="#event-dir" x="0" y="0" transform="translate(0 32) rotate(270)"></use>
</symbol>
<image id="svg-asset-rest-forbidden" href="/MightAndMagicJResource/asset/map/rest-forbidden.png" width="32" height="32" />
<image id="svg-asset-pos-ini" href="/MightAndMagicJResource/asset/map/pos-ini.png" width="32" height="32" />
<image id="svg-asset-pos-giveup" href="/MightAndMagicJResource/asset/map/pos-giveup.png" width="32" height="32" />
</defs>
<defs>
<symbol id="svg-cell-0-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
<use href="#svg-asset-event-dir-east" x="0" y="0"></use>
<use href="#svg-asset-event-dir-south" x="0" y="0"></use>
<use href="#svg-asset-pos-ini" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-12-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-14-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-0" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-10-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-1" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
<use href="#svg-asset-event-dir-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-12-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-2" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-3" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-dark" x="0" y="0"></use>
<line x1="32" y1="0" x2="0" y2="32" stroke="black" />
<use href="#svg-asset-rest-forbidden" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-4" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-1-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-3-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-5-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-5" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-13-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-15-6" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-1-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-3-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-5-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-9-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-7" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-14-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-8" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-0-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-1-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-3-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-5-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-9" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-13-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-15-10" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-1-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-3-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-5-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-11" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-14-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-12" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-0-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-1-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-3-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-5-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-downstairs" x="8" y="8"></use>
<use href="#svg-asset-event-dir-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-13" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-1-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-3-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-5-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-7-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-10-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-east" x="0" y="0"></use>
<use href="#svg-asset-pos-giveup" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-13-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-encounter" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-15-14" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-0-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-1-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-2-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-3-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-4-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-5-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-6-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
<use href="#svg-asset-icon-event" x="8" y="8"></use>
</symbol>
<symbol id="svg-cell-7-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-8-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-9-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-10-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-11-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-mountain-closed-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-12-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-west" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-13-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-14-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-south" x="0" y="0"></use>
</symbol>
<symbol id="svg-cell-15-15" width="32" height="32" viewbox="0 0 32 32">
<use href="#svg-asset-cell-bg-light" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-north" x="0" y="0"></use>
<use href="#svg-asset-boundary-forest-open-east" x="0" y="0"></use>
</symbol>
</defs>
<rect x="0" y="0" width="593" height="33" stroke="none" fill="#404040" />
<rect x="0" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="33" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="66" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="99" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="132" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="165" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="198" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="231" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="264" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="297" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="330" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="363" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="396" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="429" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="462" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="495" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="528" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="0" width="32" height="32" stroke="none" fill="black" />
<use href="#svg-asset-num-00" x="41" y="8"></use>
<use href="#svg-asset-num-01" x="74" y="8"></use>
<use href="#svg-asset-num-02" x="107" y="8"></use>
<use href="#svg-asset-num-03" x="140" y="8"></use>
<use href="#svg-asset-num-04" x="173" y="8"></use>
<use href="#svg-asset-num-05" x="206" y="8"></use>
<use href="#svg-asset-num-06" x="239" y="8"></use>
<use href="#svg-asset-num-07" x="272" y="8"></use>
<use href="#svg-asset-num-08" x="305" y="8"></use>
<use href="#svg-asset-num-09" x="338" y="8"></use>
<use href="#svg-asset-num-10" x="371" y="8"></use>
<use href="#svg-asset-num-11" x="404" y="8"></use>
<use href="#svg-asset-num-12" x="437" y="8"></use>
<use href="#svg-asset-num-13" x="470" y="8"></use>
<use href="#svg-asset-num-14" x="503" y="8"></use>
<use href="#svg-asset-num-15" x="536" y="8"></use>
<rect x="0" y="560" width="593" height="33" stroke="none" fill="#404040" />
<rect x="0" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="33" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="66" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="99" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="132" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="165" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="198" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="231" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="264" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="297" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="330" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="363" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="396" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="429" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="462" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="495" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="528" y="561" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="561" width="32" height="32" stroke="none" fill="black" />
<use href="#svg-asset-num-00" x="41" y="569"></use>
<use href="#svg-asset-num-01" x="74" y="569"></use>
<use href="#svg-asset-num-02" x="107" y="569"></use>
<use href="#svg-asset-num-03" x="140" y="569"></use>
<use href="#svg-asset-num-04" x="173" y="569"></use>
<use href="#svg-asset-num-05" x="206" y="569"></use>
<use href="#svg-asset-num-06" x="239" y="569"></use>
<use href="#svg-asset-num-07" x="272" y="569"></use>
<use href="#svg-asset-num-08" x="305" y="569"></use>
<use href="#svg-asset-num-09" x="338" y="569"></use>
<use href="#svg-asset-num-10" x="371" y="569"></use>
<use href="#svg-asset-num-11" x="404" y="569"></use>
<use href="#svg-asset-num-12" x="437" y="569"></use>
<use href="#svg-asset-num-13" x="470" y="569"></use>
<use href="#svg-asset-num-14" x="503" y="569"></use>
<use href="#svg-asset-num-15" x="536" y="569"></use>
<rect x="0" y="0" width="33" height="593" stroke="none" fill="#404040" />
<rect x="0" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="33" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="66" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="99" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="132" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="165" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="198" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="231" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="264" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="297" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="330" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="363" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="396" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="429" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="462" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="495" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="528" width="32" height="32" stroke="none" fill="black" />
<rect x="0" y="561" width="32" height="32" stroke="none" fill="black" />
<use href="#svg-asset-num-00" x="8" y="536"></use>
<use href="#svg-asset-num-01" x="8" y="503"></use>
<use href="#svg-asset-num-02" x="8" y="470"></use>
<use href="#svg-asset-num-03" x="8" y="437"></use>
<use href="#svg-asset-num-04" x="8" y="404"></use>
<use href="#svg-asset-num-05" x="8" y="371"></use>
<use href="#svg-asset-num-06" x="8" y="338"></use>
<use href="#svg-asset-num-07" x="8" y="305"></use>
<use href="#svg-asset-num-08" x="8" y="272"></use>
<use href="#svg-asset-num-09" x="8" y="239"></use>
<use href="#svg-asset-num-10" x="8" y="206"></use>
<use href="#svg-asset-num-11" x="8" y="173"></use>
<use href="#svg-asset-num-12" x="8" y="140"></use>
<use href="#svg-asset-num-13" x="8" y="107"></use>
<use href="#svg-asset-num-14" x="8" y="74"></use>
<use href="#svg-asset-num-15" x="8" y="41"></use>
<rect x="560" y="0" width="33" height="593" stroke="none" fill="#404040" />
<rect x="561" y="0" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="33" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="66" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="99" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="132" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="165" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="198" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="231" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="264" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="297" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="330" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="363" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="396" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="429" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="462" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="495" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="528" width="32" height="32" stroke="none" fill="black" />
<rect x="561" y="561" width="32" height="32" stroke="none" fill="black" />
<use href="#svg-asset-num-00" x="569" y="536"></use>
<use href="#svg-asset-num-01" x="569" y="503"></use>
<use href="#svg-asset-num-02" x="569" y="470"></use>
<use href="#svg-asset-num-03" x="569" y="437"></use>
<use href="#svg-asset-num-04" x="569" y="404"></use>
<use href="#svg-asset-num-05" x="569" y="371"></use>
<use href="#svg-asset-num-06" x="569" y="338"></use>
<use href="#svg-asset-num-07" x="569" y="305"></use>
<use href="#svg-asset-num-08" x="569" y="272"></use>
<use href="#svg-asset-num-09" x="569" y="239"></use>
<use href="#svg-asset-num-10" x="569" y="206"></use>
<use href="#svg-asset-num-11" x="569" y="173"></use>
<use href="#svg-asset-num-12" x="569" y="140"></use>
<use href="#svg-asset-num-13" x="569" y="107"></use>
<use href="#svg-asset-num-14" x="569" y="74"></use>
<use href="#svg-asset-num-15" x="569" y="41"></use>
<rect x="33" y="33" width="527" height="527" stroke="none" fill="black" />
<use href="#svg-cell-0-0" x="33" y="528"><title>(0, 0)</title></use>
<use href="#svg-cell-0-1" x="33" y="495"><title>(0, 1)</title></use>
<use href="#svg-cell-0-2" x="33" y="462"><title>(0, 2) 西: アンレコ・グリア (木登りクエスト)</title></use>
<use href="#svg-cell-0-3" x="33" y="429"><title>(0, 3)</title></use>
<use href="#svg-cell-0-4" x="33" y="396"><title>(0, 4)</title></use>
<use href="#svg-cell-0-5" x="33" y="363"><title>(0, 5) 登れる木</title></use>
<use href="#svg-cell-0-6" x="33" y="330"><title>(0, 6)</title></use>
<use href="#svg-cell-0-7" x="33" y="297"><title>(0, 7) 登れる木</title></use>
<use href="#svg-cell-0-8" x="33" y="264"><title>(0, 8)</title></use>
<use href="#svg-cell-0-9" x="33" y="231"><title>(0, 9) 登れる木</title></use>
<use href="#svg-cell-0-10" x="33" y="198"><title>(0, 10)</title></use>
<use href="#svg-cell-0-11" x="33" y="165"><title>(0, 11) 登れる木</title></use>
<use href="#svg-cell-0-12" x="33" y="132"><title>(0, 12)</title></use>
<use href="#svg-cell-0-13" x="33" y="99"><title>(0, 13) 登れる木</title></use>
<use href="#svg-cell-0-14" x="33" y="66"><title>(0, 14)</title></use>
<use href="#svg-cell-0-15" x="33" y="33"><title>(0, 15) 登れる木</title></use>
<use href="#svg-cell-1-0" x="66" y="528"><title>(1, 0)</title></use>
<use href="#svg-cell-1-1" x="66" y="495"><title>(1, 1)</title></use>
<use href="#svg-cell-1-2" x="66" y="462"><title>(1, 2)</title></use>
<use href="#svg-cell-1-3" x="66" y="429"><title>(1, 3)</title></use>
<use href="#svg-cell-1-4" x="66" y="396"><title>(1, 4)</title></use>
<use href="#svg-cell-1-5" x="66" y="363"><title>(1, 5)</title></use>
<use href="#svg-cell-1-6" x="66" y="330"><title>(1, 6)</title></use>
<use href="#svg-cell-1-7" x="66" y="297"><title>(1, 7)</title></use>
<use href="#svg-cell-1-8" x="66" y="264"><title>(1, 8)</title></use>
<use href="#svg-cell-1-9" x="66" y="231"><title>(1, 9)</title></use>
<use href="#svg-cell-1-10" x="66" y="198"><title>(1, 10)</title></use>
<use href="#svg-cell-1-11" x="66" y="165"><title>(1, 11)</title></use>
<use href="#svg-cell-1-12" x="66" y="132"><title>(1, 12)</title></use>
<use href="#svg-cell-1-13" x="66" y="99"><title>(1, 13)</title></use>
<use href="#svg-cell-1-14" x="66" y="66"><title>(1, 14)</title></use>
<use href="#svg-cell-1-15" x="66" y="33"><title>(1, 15)</title></use>
<use href="#svg-cell-2-0" x="99" y="528"><title>(2, 0)</title></use>
<use href="#svg-cell-2-1" x="99" y="495"><title>(2, 1)</title></use>
<use href="#svg-cell-2-2" x="99" y="462"><title>(2, 2)</title></use>
<use href="#svg-cell-2-3" x="99" y="429"><title>(2, 3)</title></use>
<use href="#svg-cell-2-4" x="99" y="396"><title>(2, 4)</title></use>
<use href="#svg-cell-2-5" x="99" y="363"><title>(2, 5) 登れる木</title></use>
<use href="#svg-cell-2-6" x="99" y="330"><title>(2, 6)</title></use>
<use href="#svg-cell-2-7" x="99" y="297"><title>(2, 7) 登れる木</title></use>
<use href="#svg-cell-2-8" x="99" y="264"><title>(2, 8)</title></use>
<use href="#svg-cell-2-9" x="99" y="231"><title>(2, 9) 登れる木</title></use>
<use href="#svg-cell-2-10" x="99" y="198"><title>(2, 10)</title></use>
<use href="#svg-cell-2-11" x="99" y="165"><title>(2, 11) 登れる木</title></use>
<use href="#svg-cell-2-12" x="99" y="132"><title>(2, 12)</title></use>
<use href="#svg-cell-2-13" x="99" y="99"><title>(2, 13) 登れる木</title></use>
<use href="#svg-cell-2-14" x="99" y="66"><title>(2, 14)</title></use>
<use href="#svg-cell-2-15" x="99" y="33"><title>(2, 15) 登れる木</title></use>
<use href="#svg-cell-3-0" x="132" y="528"><title>(3, 0)</title></use>
<use href="#svg-cell-3-1" x="132" y="495"><title>(3, 1)</title></use>
<use href="#svg-cell-3-2" x="132" y="462"><title>(3, 2)</title></use>
<use href="#svg-cell-3-3" x="132" y="429"><title>(3, 3)</title></use>
<use href="#svg-cell-3-4" x="132" y="396"><title>(3, 4)</title></use>
<use href="#svg-cell-3-5" x="132" y="363"><title>(3, 5)</title></use>
<use href="#svg-cell-3-6" x="132" y="330"><title>(3, 6)</title></use>
<use href="#svg-cell-3-7" x="132" y="297"><title>(3, 7)</title></use>
<use href="#svg-cell-3-8" x="132" y="264"><title>(3, 8)</title></use>
<use href="#svg-cell-3-9" x="132" y="231"><title>(3, 9)</title></use>
<use href="#svg-cell-3-10" x="132" y="198"><title>(3, 10)</title></use>
<use href="#svg-cell-3-11" x="132" y="165"><title>(3, 11)</title></use>
<use href="#svg-cell-3-12" x="132" y="132"><title>(3, 12)</title></use>
<use href="#svg-cell-3-13" x="132" y="99"><title>(3, 13)</title></use>
<use href="#svg-cell-3-14" x="132" y="66"><title>(3, 14)</title></use>
<use href="#svg-cell-3-15" x="132" y="33"><title>(3, 15)</title></use>
<use href="#svg-cell-4-0" x="165" y="528"><title>(4, 0)</title></use>
<use href="#svg-cell-4-1" x="165" y="495"><title>(4, 1)</title></use>
<use href="#svg-cell-4-2" x="165" y="462"><title>(4, 2)</title></use>
<use href="#svg-cell-4-3" x="165" y="429"><title>(4, 3)</title></use>
<use href="#svg-cell-4-4" x="165" y="396"><title>(4, 4)</title></use>
<use href="#svg-cell-4-5" x="165" y="363"><title>(4, 5) 登れる木</title></use>
<use href="#svg-cell-4-6" x="165" y="330"><title>(4, 6)</title></use>
<use href="#svg-cell-4-7" x="165" y="297"><title>(4, 7) 登れる木</title></use>
<use href="#svg-cell-4-8" x="165" y="264"><title>(4, 8)</title></use>
<use href="#svg-cell-4-9" x="165" y="231"><title>(4, 9) 登れる木</title></use>
<use href="#svg-cell-4-10" x="165" y="198"><title>(4, 10)</title></use>
<use href="#svg-cell-4-11" x="165" y="165"><title>(4, 11) 登れる木</title></use>
<use href="#svg-cell-4-12" x="165" y="132"><title>(4, 12)</title></use>
<use href="#svg-cell-4-13" x="165" y="99"><title>(4, 13) 登れる木</title></use>
<use href="#svg-cell-4-14" x="165" y="66"><title>(4, 14)</title></use>
<use href="#svg-cell-4-15" x="165" y="33"><title>(4, 15) 登れる木</title></use>
<use href="#svg-cell-5-0" x="198" y="528"><title>(5, 0)</title></use>
<use href="#svg-cell-5-1" x="198" y="495"><title>(5, 1)</title></use>
<use href="#svg-cell-5-2" x="198" y="462"><title>(5, 2)</title></use>
<use href="#svg-cell-5-3" x="198" y="429"><title>(5, 3)</title></use>
<use href="#svg-cell-5-4" x="198" y="396"><title>(5, 4)</title></use>
<use href="#svg-cell-5-5" x="198" y="363"><title>(5, 5)</title></use>
<use href="#svg-cell-5-6" x="198" y="330"><title>(5, 6)</title></use>
<use href="#svg-cell-5-7" x="198" y="297"><title>(5, 7)</title></use>
<use href="#svg-cell-5-8" x="198" y="264"><title>(5, 8)</title></use>
<use href="#svg-cell-5-9" x="198" y="231"><title>(5, 9)</title></use>
<use href="#svg-cell-5-10" x="198" y="198"><title>(5, 10)</title></use>
<use href="#svg-cell-5-11" x="198" y="165"><title>(5, 11)</title></use>
<use href="#svg-cell-5-12" x="198" y="132"><title>(5, 12)</title></use>
<use href="#svg-cell-5-13" x="198" y="99"><title>(5, 13)</title></use>
<use href="#svg-cell-5-14" x="198" y="66"><title>(5, 14)</title></use>
<use href="#svg-cell-5-15" x="198" y="33"><title>(5, 15)</title></use>
<use href="#svg-cell-6-0" x="231" y="528"><title>(6, 0)</title></use>
<use href="#svg-cell-6-1" x="231" y="495"><title>(6, 1)</title></use>
<use href="#svg-cell-6-2" x="231" y="462"><title>(6, 2)</title></use>
<use href="#svg-cell-6-3" x="231" y="429"><title>(6, 3)</title></use>
<use href="#svg-cell-6-4" x="231" y="396"><title>(6, 4)</title></use>
<use href="#svg-cell-6-5" x="231" y="363"><title>(6, 5)</title></use>
<use href="#svg-cell-6-6" x="231" y="330"><title>(6, 6)</title></use>
<use href="#svg-cell-6-7" x="231" y="297"><title>(6, 7)</title></use>
<use href="#svg-cell-6-8" x="231" y="264"><title>(6, 8)</title></use>
<use href="#svg-cell-6-9" x="231" y="231"><title>(6, 9)</title></use>
<use href="#svg-cell-6-10" x="231" y="198"><title>(6, 10)</title></use>
<use href="#svg-cell-6-11" x="231" y="165"><title>(6, 11)</title></use>
<use href="#svg-cell-6-12" x="231" y="132"><title>(6, 12)</title></use>
<use href="#svg-cell-6-13" x="231" y="99"><title>(6, 13)</title></use>
<use href="#svg-cell-6-14" x="231" y="66"><title>(6, 14)</title></use>
<use href="#svg-cell-6-15" x="231" y="33"><title>(6, 15) 登れる木</title></use>
<use href="#svg-cell-7-0" x="264" y="528"><title>(7, 0) 東or南: アルガリー: 南9</title></use>
<use href="#svg-cell-7-1" x="264" y="495"><title>(7, 1)</title></use>
<use href="#svg-cell-7-2" x="264" y="462"><title>(7, 2)</title></use>
<use href="#svg-cell-7-3" x="264" y="429"><title>(7, 3)</title></use>
<use href="#svg-cell-7-4" x="264" y="396"><title>(7, 4)</title></use>
<use href="#svg-cell-7-5" x="264" y="363"><title>(7, 5)</title></use>
<use href="#svg-cell-7-6" x="264" y="330"><title>(7, 6)</title></use>
<use href="#svg-cell-7-7" x="264" y="297"><title>(7, 7)</title></use>
<use href="#svg-cell-7-8" x="264" y="264"><title>(7, 8)</title></use>
<use href="#svg-cell-7-9" x="264" y="231"><title>(7, 9)</title></use>
<use href="#svg-cell-7-10" x="264" y="198"><title>(7, 10)</title></use>
<use href="#svg-cell-7-11" x="264" y="165"><title>(7, 11)</title></use>
<use href="#svg-cell-7-12" x="264" y="132"><title>(7, 12)</title></use>
<use href="#svg-cell-7-13" x="264" y="99"><title>(7, 13) 北: 鷹の目洞穴 (8, 8) への入口</title></use>
<use href="#svg-cell-7-14" x="264" y="66"><title>(7, 14)</title></use>
<use href="#svg-cell-7-15" x="264" y="33"><title>(7, 15)</title></use>
<use href="#svg-cell-8-0" x="297" y="528"><title>(8, 0)</title></use>
<use href="#svg-cell-8-1" x="297" y="495"><title>(8, 1)</title></use>
<use href="#svg-cell-8-2" x="297" y="462"><title>(8, 2)</title></use>
<use href="#svg-cell-8-3" x="297" y="429"><title>(8, 3)</title></use>
<use href="#svg-cell-8-4" x="297" y="396"><title>(8, 4)</title></use>
<use href="#svg-cell-8-5" x="297" y="363"><title>(8, 5)</title></use>
<use href="#svg-cell-8-6" x="297" y="330"><title>(8, 6)</title></use>
<use href="#svg-cell-8-7" x="297" y="297"><title>(8, 7) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-8-8" x="297" y="264"><title>(8, 8)</title></use>
<use href="#svg-cell-8-9" x="297" y="231"><title>(8, 9)</title></use>
<use href="#svg-cell-8-10" x="297" y="198"><title>(8, 10)</title></use>
<use href="#svg-cell-8-11" x="297" y="165"><title>(8, 11)</title></use>
<use href="#svg-cell-8-12" x="297" y="132"><title>(8, 12)</title></use>
<use href="#svg-cell-8-13" x="297" y="99"><title>(8, 13)</title></use>
<use href="#svg-cell-8-14" x="297" y="66"><title>(8, 14)</title></use>
<use href="#svg-cell-8-15" x="297" y="33"><title>(8, 15)</title></use>
<use href="#svg-cell-9-0" x="330" y="528"><title>(9, 0)</title></use>
<use href="#svg-cell-9-1" x="330" y="495"><title>(9, 1) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-9-2" x="330" y="462"><title>(9, 2)</title></use>
<use href="#svg-cell-9-3" x="330" y="429"><title>(9, 3)</title></use>
<use href="#svg-cell-9-4" x="330" y="396"><title>(9, 4)</title></use>
<use href="#svg-cell-9-5" x="330" y="363"><title>(9, 5)</title></use>
<use href="#svg-cell-9-6" x="330" y="330"><title>(9, 6)</title></use>
<use href="#svg-cell-9-7" x="330" y="297"><title>(9, 7)</title></use>
<use href="#svg-cell-9-8" x="330" y="264"><title>(9, 8)</title></use>
<use href="#svg-cell-9-9" x="330" y="231"><title>(9, 9)</title></use>
<use href="#svg-cell-9-10" x="330" y="198"><title>(9, 10)</title></use>
<use href="#svg-cell-9-11" x="330" y="165"><title>(9, 11)</title></use>
<use href="#svg-cell-9-12" x="330" y="132"><title>(9, 12)</title></use>
<use href="#svg-cell-9-13" x="330" y="99"><title>(9, 13)</title></use>
<use href="#svg-cell-9-14" x="330" y="66"><title>(9, 14) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-9-15" x="330" y="33"><title>(9, 15)</title></use>
<use href="#svg-cell-10-0" x="363" y="528"><title>(10, 0)</title></use>
<use href="#svg-cell-10-1" x="363" y="495"><title>(10, 1)</title></use>
<use href="#svg-cell-10-2" x="363" y="462"><title>(10, 2)</title></use>
<use href="#svg-cell-10-3" x="363" y="429"><title>(10, 3)</title></use>
<use href="#svg-cell-10-4" x="363" y="396"><title>(10, 4)</title></use>
<use href="#svg-cell-10-5" x="363" y="363"><title>(10, 5)</title></use>
<use href="#svg-cell-10-6" x="363" y="330"><title>(10, 6)</title></use>
<use href="#svg-cell-10-7" x="363" y="297"><title>(10, 7)</title></use>
<use href="#svg-cell-10-8" x="363" y="264"><title>(10, 8)</title></use>
<use href="#svg-cell-10-9" x="363" y="231"><title>(10, 9)</title></use>
<use href="#svg-cell-10-10" x="363" y="198"><title>(10, 10)</title></use>
<use href="#svg-cell-10-11" x="363" y="165"><title>(10, 11)</title></use>
<use href="#svg-cell-10-12" x="363" y="132"><title>(10, 12)</title></use>
<use href="#svg-cell-10-13" x="363" y="99"><title>(10, 13)</title></use>
<use href="#svg-cell-10-14" x="363" y="66"><title>(10, 14)</title></use>
<use href="#svg-cell-10-15" x="363" y="33"><title>(10, 15)</title></use>
<use href="#svg-cell-11-0" x="396" y="528"><title>(11, 0) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-11-1" x="396" y="495"><title>(11, 1)</title></use>
<use href="#svg-cell-11-2" x="396" y="462"><title>(11, 2) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-11-3" x="396" y="429"><title>(11, 3)</title></use>
<use href="#svg-cell-11-4" x="396" y="396"><title>(11, 4)</title></use>
<use href="#svg-cell-11-5" x="396" y="363"><title>(11, 5)</title></use>
<use href="#svg-cell-11-6" x="396" y="330"><title>(11, 6)</title></use>
<use href="#svg-cell-11-7" x="396" y="297"><title>(11, 7)</title></use>
<use href="#svg-cell-11-8" x="396" y="264"><title>(11, 8)</title></use>
<use href="#svg-cell-11-9" x="396" y="231"><title>(11, 9)</title></use>
<use href="#svg-cell-11-10" x="396" y="198"><title>(11, 10)</title></use>
<use href="#svg-cell-11-11" x="396" y="165"><title>(11, 11)</title></use>
<use href="#svg-cell-11-12" x="396" y="132"><title>(11, 12)</title></use>
<use href="#svg-cell-11-13" x="396" y="99"><title>(11, 13)</title></use>
<use href="#svg-cell-11-14" x="396" y="66"><title>(11, 14)</title></use>
<use href="#svg-cell-11-15" x="396" y="33"><title>(11, 15)</title></use>
<use href="#svg-cell-12-0" x="429" y="528"><title>(12, 0)</title></use>
<use href="#svg-cell-12-1" x="429" y="495"><title>(12, 1)</title></use>
<use href="#svg-cell-12-2" x="429" y="462"><title>(12, 2)</title></use>
<use href="#svg-cell-12-3" x="429" y="429"><title>(12, 3)</title></use>
<use href="#svg-cell-12-4" x="429" y="396"><title>(12, 4)</title></use>
<use href="#svg-cell-12-5" x="429" y="363"><title>(12, 5)</title></use>
<use href="#svg-cell-12-6" x="429" y="330"><title>(12, 6) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-12-7" x="429" y="297"><title>(12, 7)</title></use>
<use href="#svg-cell-12-8" x="429" y="264"><title>(12, 8)</title></use>
<use href="#svg-cell-12-9" x="429" y="231"><title>(12, 9)</title></use>
<use href="#svg-cell-12-10" x="429" y="198"><title>(12, 10) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-12-11" x="429" y="165"><title>(12, 11)</title></use>
<use href="#svg-cell-12-12" x="429" y="132"><title>(12, 12)</title></use>
<use href="#svg-cell-12-13" x="429" y="99"><title>(12, 13)</title></use>
<use href="#svg-cell-12-14" x="429" y="66"><title>(12, 14) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-12-15" x="429" y="33"><title>(12, 15)</title></use>
<use href="#svg-cell-13-0" x="462" y="528"><title>(13, 0) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-13-1" x="462" y="495"><title>(13, 1)</title></use>
<use href="#svg-cell-13-2" x="462" y="462"><title>(13, 2)</title></use>
<use href="#svg-cell-13-3" x="462" y="429"><title>(13, 3)</title></use>
<use href="#svg-cell-13-4" x="462" y="396"><title>(13, 4)</title></use>
<use href="#svg-cell-13-5" x="462" y="363"><title>(13, 5)</title></use>
<use href="#svg-cell-13-6" x="462" y="330"><title>(13, 6)</title></use>
<use href="#svg-cell-13-7" x="462" y="297"><title>(13, 7)</title></use>
<use href="#svg-cell-13-8" x="462" y="264"><title>(13, 8) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-13-9" x="462" y="231"><title>(13, 9)</title></use>
<use href="#svg-cell-13-10" x="462" y="198"><title>(13, 10)</title></use>
<use href="#svg-cell-13-11" x="462" y="165"><title>(13, 11)</title></use>
<use href="#svg-cell-13-12" x="462" y="132"><title>(13, 12) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-13-13" x="462" y="99"><title>(13, 13)</title></use>
<use href="#svg-cell-13-14" x="462" y="66"><title>(13, 14)</title></use>
<use href="#svg-cell-13-15" x="462" y="33"><title>(13, 15)</title></use>
<use href="#svg-cell-14-0" x="495" y="528"><title>(14, 0)</title></use>
<use href="#svg-cell-14-1" x="495" y="495"><title>(14, 1)</title></use>
<use href="#svg-cell-14-2" x="495" y="462"><title>(14, 2)</title></use>
<use href="#svg-cell-14-3" x="495" y="429"><title>(14, 3)</title></use>
<use href="#svg-cell-14-4" x="495" y="396"><title>(14, 4)</title></use>
<use href="#svg-cell-14-5" x="495" y="363"><title>(14, 5)</title></use>
<use href="#svg-cell-14-6" x="495" y="330"><title>(14, 6) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-14-7" x="495" y="297"><title>(14, 7)</title></use>
<use href="#svg-cell-14-8" x="495" y="264"><title>(14, 8)</title></use>
<use href="#svg-cell-14-9" x="495" y="231"><title>(14, 9)</title></use>
<use href="#svg-cell-14-10" x="495" y="198"><title>(14, 10) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-14-11" x="495" y="165"><title>(14, 11)</title></use>
<use href="#svg-cell-14-12" x="495" y="132"><title>(14, 12)</title></use>
<use href="#svg-cell-14-13" x="495" y="99"><title>(14, 13)</title></use>
<use href="#svg-cell-14-14" x="495" y="66"><title>(14, 14) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-14-15" x="495" y="33"><title>(14, 15)</title></use>
<use href="#svg-cell-15-0" x="528" y="528"><title>(15, 0)</title></use>
<use href="#svg-cell-15-1" x="528" y="495"><title>(15, 1)</title></use>
<use href="#svg-cell-15-2" x="528" y="462"><title>(15, 2)</title></use>
<use href="#svg-cell-15-3" x="528" y="429"><title>(15, 3)</title></use>
<use href="#svg-cell-15-4" x="528" y="396"><title>(15, 4)</title></use>
<use href="#svg-cell-15-5" x="528" y="363"><title>(15, 5)</title></use>
<use href="#svg-cell-15-6" x="528" y="330"><title>(15, 6)</title></use>
<use href="#svg-cell-15-7" x="528" y="297"><title>(15, 7)</title></use>
<use href="#svg-cell-15-8" x="528" y="264"><title>(15, 8) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-15-9" x="528" y="231"><title>(15, 9)</title></use>
<use href="#svg-cell-15-10" x="528" y="198"><title>(15, 10)</title></use>
<use href="#svg-cell-15-11" x="528" y="165"><title>(15, 11)</title></use>
<use href="#svg-cell-15-12" x="528" y="132"><title>(15, 12) エンカウント (ランダム編成)</title></use>
<use href="#svg-cell-15-13" x="528" y="99"><title>(15, 13)</title></use>
<use href="#svg-cell-15-14" x="528" y="66"><title>(15, 14)</title></use>
<use href="#svg-cell-15-15" x="528" y="33"><title>(15, 15)</title></use>
</svg>
<!-- }}} -->

