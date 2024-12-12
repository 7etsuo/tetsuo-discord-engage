# tetsuo-discord-engage


INSTALL:
```
 git clone https://github.com/tetsuo-ai/tetsuo-discord-engage
 cd tetsuo-discord-engage/
 python -m venv .venv
 source .venv/bin/activate
 pip install -r requirements.txt
 playwright install --with-deps --only-shell
```
EXAMPLE:
```
(.venv) $ time python scrape_twitter.py
{'__typename': 'Tweet', 'rest_id': '1664267318053179398', 'core': {'user_results': {'result': {'__typename': 'User', 'id': 'VXNlcjoxMzEwNjIzMDgxMzAwNDAyMTc4', 'rest_id': '1310623081300402178', 'affiliates_highlighted_label': {}, 'is_blue_verified': True, 'profile_image_shape': 'Circle', 'legacy': {'created_at': 'Mon Sep 28 16:51:22 +0000 2020', 'default_profile': True, 'default_profile_image': False, 'description': 'API products for developers:\n- Web Scraping API: scrape any page\n- Screenshot API: screenshot any website\n- Extraction API: parse data using AI', 'entities': {'description': {'urls': []}, 'url': {'urls': [{'display_url': 'scrapfly.io', 'expanded_url': 'https://scrapfly.io', 'url': 'https://t.co/1Is3k6KzyM', 'indices': [0, 23]}]}}, 'fast_followers_count': 0, 'favourites_count': 38, 'followers_count': 250, 'friends_count': 4, 'has_custom_timelines': True, 'is_translator': False, 'listed_count': 3, 'location': 'Paris', 'media_count': 38, 'name': 'Scrapfly', 'normal_followers_count': 250, 'pinned_tweet_ids_str': ['1863616315174551787'], 'possibly_sensitive': False, 'profile_banner_url': 'https://pbs.twimg.com/profile_banners/1310623081300402178/1601320645', 'profile_image_url_https': 'https://pbs.twimg.com/profile_images/1310658795715076098/XedZDwC7_normal.jpg', 'profile_interstitial_type': '', 'screen_name': 'Scrapfly_dev', 'statuses_count': 151, 'translator_type': 'none', 'url': 'https://t.co/1Is3k6KzyM', 'verified': False, 'withheld_in_countries': []}, 'tipjar_settings': {'is_enabled': False, 'bandcamp_handle': '', 'bitcoin_handle': '', 'cash_app_handle': '', 'ethereum_handle': '', 'gofundme_handle': '', 'patreon_handle': '', 'pay_pal_handle': '', 'venmo_handle': ''}}}}, 'unmention_data': {}, 'edit_control': {'edit_tweet_ids': ['1664267318053179398'], 'editable_until_msecs': '1685629023000', 'is_edit_eligible': True, 'edits_remaining': '5'}, 'is_translatable': False, 'views': {'count': '1526', 'state': 'EnabledWithCount'}, 'source': '<a href="https://zapier.com/" rel="nofollow">Zapier.com</a>', 'legacy': {'bookmark_count': 0, 'bookmarked': False, 'created_at': 'Thu Jun 01 13:47:03 +0000 2023', 'conversation_id_str': '1664267318053179398', 'display_text_range': [0, 122], 'entities': {'hashtags': [], 'media': [{'display_url': 'pic.x.com/zLjDlxdKee', 'expanded_url': 'https://x.com/Scrapfly_dev/status/1664267318053179398/photo/1', 'id_str': '1664267314160607232', 'indices': [123, 146], 'media_key': '3_1664267314160607232', 'media_url_https': 'https://pbs.twimg.com/media/FxiqTffWIAALf7O.png', 'type': 'photo', 'url': 'https://t.co/zLjDlxdKee', 'ext_media_availability': {'status': 'Available'}, 'features': {'large': {'faces': []}, 'medium': {'faces': []}, 'small': {'faces': []}, 'orig': {'faces': []}}, 'sizes': {'large': {'h': 416, 'w': 796, 'resize': 'fit'}, 'medium': {'h': 416, 'w': 796, 'resize': 'fit'}, 'small': {'h': 355, 'w': 680, 'resize': 'fit'}, 'thumb': {'h': 150, 'w': 150, 'resize': 'crop'}}, 'original_info': {'height': 416, 'width': 796, 'focus_rects': [{'x': 27, 'y': 0, 'w': 743, 'h': 416}, {'x': 190, 'y': 0, 'w': 416, 'h': 416}, {'x': 216, 'y': 0, 'w': 365, 'h': 416}, {'x': 294, 'y': 0, 'w': 208, 'h': 416}, {'x': 0, 'y': 0, 'w': 796, 'h': 416}]}, 'media_results': {'result': {'media_key': '3_1664267314160607232'}}}], 'symbols': [], 'timestamps': [], 'urls': [{'display_url': 'scrapfly.io/blog/top-10-we…', 'expanded_url': 'https://scrapfly.io/blog/top-10-web-scraping-libraries-in-python/', 'url': 'https://t.co/d2iFdAV2LJ', 'indices': [99, 122]}], 'user_mentions': []}, 'extended_entities': {'media': [{'display_url': 'pic.x.com/zLjDlxdKee', 'expanded_url': 'https://x.com/Scrapfly_dev/status/1664267318053179398/photo/1', 'id_str': '1664267314160607232', 'indices': [123, 146], 'media_key': '3_1664267314160607232', 'media_url_https': 'https://pbs.twimg.com/media/FxiqTffWIAALf7O.png', 'type': 'photo', 'url': 'https://t.co/zLjDlxdKee', 'ext_media_availability': {'status': 'Available'}, 'features': {'large': {'faces': []}, 'medium': {'faces': []}, 'small': {'faces': []}, 'orig': {'faces': []}}, 'sizes': {'large': {'h': 416, 'w': 796, 'resize': 'fit'}, 'medium': {'h': 416, 'w': 796, 'resize': 'fit'}, 'small': {'h': 355, 'w': 680, 'resize': 'fit'}, 'thumb': {'h': 150, 'w': 150, 'resize': 'crop'}}, 'original_info': {'height': 416, 'width': 796, 'focus_rects': [{'x': 27, 'y': 0, 'w': 743, 'h': 416}, {'x': 190, 'y': 0, 'w': 416, 'h': 416}, {'x': 216, 'y': 0, 'w': 365, 'h': 416}, {'x': 294, 'y': 0, 'w': 208, 'h': 416}, {'x': 0, 'y': 0, 'w': 796, 'h': 416}]}, 'media_results': {'result': {'media_key': '3_1664267314160607232'}}}]}, 'favorite_count': 3, 'favorited': False, 'full_text': 'A new blog post has been published! \n\nTop 10 Web Scraping Packages for Python 🤖\n\nCheckout it out 👇\nhttps://t.co/d2iFdAV2LJ https://t.co/zLjDlxdKee', 'is_quote_status': False, 'lang': 'en', 'possibly_sensitive': False, 'possibly_sensitive_editable': True, 'quote_count': 0, 'reply_count': 7, 'retweet_count': 0, 'retweeted': False, 'user_id_str': '1310623081300402178', 'id_str': '1664267318053179398'}}

real    0m3.699s
user    0m1.880s
sys     0m0.906s
