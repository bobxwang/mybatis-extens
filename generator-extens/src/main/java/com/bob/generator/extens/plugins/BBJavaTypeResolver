package com.bob.gennerator.extens.plugins;

import org.mybatis.generator.api.dom.java.FullyQualifiedJavaType;
import org.mybatis.generator.internal.types.JavaTypeResolverDefaultImpl;

import java.sql.Types;
import java.time.LocalDate;
import java.time.LocalDateTime;
import java.time.LocalTime;

/**
 * 〈〉
 *
 * @author wangxiang
 * @create 2019-01-09
 */
public class BBJavaTypeResolver extends JavaTypeResolverDefaultImpl {

    public MyJavaTypeResolver() {
        super();
        super.typeMap.put(Types.DATE, new JavaTypeResolverDefaultImpl.JdbcTypeInformation("DATE", new FullyQualifiedJavaType(LocalDate.class.getName())));
        super.typeMap.put(Types.TIME, new JavaTypeResolverDefaultImpl.JdbcTypeInformation("TIME", new FullyQualifiedJavaType(LocalTime.class.getName())));
        super.typeMap.put(Types.TIMESTAMP, new JavaTypeResolverDefaultImpl.JdbcTypeInformation("TIMESTAMP", new FullyQualifiedJavaType(LocalDateTime.class.getName())));
        super.typeMap.put(
            Types.SMALLINT,
            new JavaTypeResolverDefaultImpl.JdbcTypeInformation(
                "SMALLINT", new FullyQualifiedJavaType(Integer.class.getName())));
        super.typeMap.put(
            Types.TINYINT,
            new JavaTypeResolverDefaultImpl.JdbcTypeInformation(
                    "TINYINT", new FullyQualifiedJavaType(Integer.class.getName())));
    }
}
