# spark-test-exercise

решение задачи https://github.com/anvarknian/spark-training

файл с данными надо положить отдельно в оговоренную в задаче папку, он слишком большой для гита

как и требуется в условии, задача решена тремя способами, чтобы проверить их надо раскоментировать соответствующую строчку в функции timeUsageByLifePeriod
а две другие закоментировать

    //    using the programmatic API
    //    val finalDf = timeUsageGrouped(summaryDf)

    //    using plain sql
    //    val finalDf = timeUsageGroupedSql(summaryDf)

    //  using dataset
    val finalDf = timeUsageGroupedTyped(timeUsageSummaryTyped(summaryDf))
    
по умолчанию включен последний вариант через dataSet
