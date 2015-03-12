# Duration From Now #
it print out time diff, how long before.

english, korean message available.

```
test code:
public void testSpace() {
    DurationFromNow.setLocale(Locale.ENGLISH);
    String now = "20070812092303";
    assertEquals("2 days ago", 
            DurationFromNow.getTimeDiffLabel("20070810092303", now));
    assertEquals("3 days ago", 
            DurationFromNow.getTimeDiffLabel("20070809092303", now));
    assertEquals("10 days ago", 
            DurationFromNow.getTimeDiffLabel("20070802092303", now));
    assertEquals("11 days ago", 
            DurationFromNow.getTimeDiffLabel("20070801092303", now));
    assertEquals("12 days ago", 
            DurationFromNow.getTimeDiffLabel("20070731092303", now));
    assertEquals("13 days ago", 
            DurationFromNow.getTimeDiffLabel("20070730092303", now));
    assertEquals("23 days ago", 
            DurationFromNow.getTimeDiffLabel("20070720092303", now));
    assertEquals("29 days ago", 
            DurationFromNow.getTimeDiffLabel("20070714092303", now));
}

```