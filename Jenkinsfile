@Library('approval-shared-library@master') _
import com.visma.approval.jenkins.MavenLibraryConfiguration

buildSemVerMavenLibrary(new MavenLibraryConfiguration()
        .jdk("JDK 11")
        .versionTagPrefix("sv")
        .executeJMHTests(false)
        .maven("Maven 3.9.x"))
